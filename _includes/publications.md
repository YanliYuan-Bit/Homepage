<!-- 
This code generates a list of publications with various details such as title, authors, conference, links, and citation information. It uses a for loop to iterate over the publications data and dynamically generates the HTML markup for each publication.

The publications are displayed in an ordered list (<ol>) with each publication represented as a list item (<li>). The list item contains a row (<div class="pub-row">) with two columns: one for the publication image and abbreviation, and the other for the publication details.

The publication image is displayed using an <img> tag with the source specified by the "link.image" variable. The abbreviation of the conference is displayed as a badge using the <abbr> tag.

The publication details such as title, authors, and conference are displayed within their respective <div> tags.

The links associated with the publication (PDF, code, project page, BibTex) are displayed as buttons using the <a> tag with the appropriate href and target attributes. The buttons are styled using CSS classes.

If there are any additional notes or other information associated with the publication, they are displayed using the <strong> and <i> tags.

If the publication has citation information available, it is displayed within a nested for loop. The citation information includes the title, year, number of citations, and a link to the "Cited By" page.

The code is written in Markdown and is intended to be used in a website or web page to display a list of publications.

-->
<h1 id="publications"></h1>

<h2 style="margin: 30px 0px -15px;"> Selected Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=7La0oUa0e5IC&hl=en" target="_blank" style="font-size:15px;">Complete List</a>]</h2>

<ul>
<li>* corresponding author</li>
<li><strong>Yanli Yuan</strong>,  B. Wang, C. Zhang, Z. Xiong, C. Li, L. Zhu. “Towards Efficient and Robust Federated Unlearning in IoT Networks”, IEEE Internet of Things Journal (IOTJ), 2024. (SCI 一区, Top 期刊).</li>
<li><strong>Yanli Yuan</strong>,  D. W. Soh, K. Guo, Z. Xiong*, and T. Q. S. Quek. “Joint Network Topology Inference via Structured Fusion Regularization”, IEEE Transactions on Knowledge and Data Engineering (TKDE), 2023. (CCF A).</li>
<li><strong>Yanli Yuan</strong>, D. Lei, Q. Fan, K. Zhao, L. Zhu, C. Zhang, “Achieving Adaptive Privacy-Preserving Graph Neural Networks Training in Cloud Environment”, IEEE 12th International Conference on Information, Communication and Networks (ICICN), 181-186, 2024. <strong>(Best Paper Award)</strong>. </li>
<li>W. Yang, Z. Xiong, <strong>Yanli Yuan*</strong>, W. Jiang, Tony Q.S. Quek, Merouane Debbah, “Achieving Adaptive Privacy-Preserving Graph Neural Networks Training in Cloud Environment”, IEEE 12th International Conference on Information, Communication and Networks (ICICN), 181-186, 2024. <strong>(Best Paper Award)</strong>. </li>
<!-- <li><strong>[DEC. 2023]</strong> The <span style="color:#e74d3c"><a href="https://goindex.chen-song90.workers.dev">Googledrive index</a></span> has been now integrated to the webblog.</li>
<li><strong>[DEC. 2023]</strong> The <span style="color:#e74d3c"><a href="https://songchen.science/blog/gallery/">Hitchhiker's Gallery</a></span> has been released, thanks to anzai's <span style="color:#e74d3c"><a href="https://github.com/anzai249/easy-masonry/tree/main">work: easy-masonry</a></span> </li>
<li><strong>[NOV. 2023]</strong> The <span style="color:#e74d3c"><a href="https://bemagic-etn.eu/news/80-bemagic-final-event">Final Event of the BeMAGIC project</a></span> will take place in the Universitat Autònoma de Barcelona, Spain, on 14-15 December. </li>
<li><strong>[NOV. 2023]</strong> AHEMS: <span style="color:#e74d3c"><a href="https://hitchhiker.azurewebsites.net/?/AHEMS/">Anomalous Hall Effect Measurement System</a></span> has been released.</li>
<div id="newsmore" style="display:none">
<li><strong>[NOV. 2023]</strong> <span style="color:#e74d3c"><a href="https://hitchhiker.azurewebsites.net/?/I-V/">I-V Measurement System</a></span> has been released.</li>
<li><strong>[OCT. 2023]</strong> The Tech Blog <span style="color:#e74d3c"><a href="https://songchen.science/blog/">"The Hitchhiker's Guide to Galaxy"</a></span> has now integrated an <span style="color:#e74d3c"><a href="https://hitchhiker.azurewebsites.net">onedrive file list program</a></span> implemented by calling API.</li>
<li><strong>[OCT. 2023]</strong> The Tech Blog <span style="color:#e74d3c"><a href="https://songchen.science/blog/">"The Hitchhiker's Guide to Galaxy"</a></span> has now a <span style="color:#e74d3c"><a href="https://songchen.science/blog/zh-CN">chinese version</a></span>. The content inside can be separately edited. Later maybe a german version.</li>
<li><strong>[OCT. 2023]</strong> A Tech Blog <span style="color:#e74d3c"><a href="https://songchen.science/blog/">"The Hitchhiker's Guide to Galaxy"</a></span> was integrated to this personal homepage, the webblog is based on <span style="color:#e74d3c"><a href="https://hexo.io/">Hexo</a></span>: a webblog framework</li>
<li> <a href="javascript:toggle_vis('newsmore')">Show more</a> </li>
<li><strong>[SEP. 2023]</strong> The BeMAGIC Final Event will be held between 14-15 December 2023 at <span style="color:#e74d3c"><a href="https://www.uab.cat/web/universitat-autonoma-de-barcelona-1345467954774.html">UAB</a></span>, Barcelona, Spain.</li>
<li><strong>[AUG. 2023]</strong> <a href="https://song-chen1.github.io/">Personal Homepage</a>, I will begin to upload some built-by-myself softwares and scripts to the <span style="color:#e74d3c"><a href="https://github.com/song-chen1/">GitHub</a></span> to help this community.</li>
<li><strong>[AUG. 2023]</strong> I will participate in the upcoming 13th Joint European Magnetic Symposia <a href="https://www.jems2023.es/">JEMS2023</a>, in the form of poster presentation with the title <span style="color:#e74d3c"><a href="./assets/files/JEMS2023_Song">Reversible magneto-Ionic effect in crystallized W-CoFeB-MgO-HfO2 ultra-thin films with perpendicular anisotropy.</a></span></li>
<li><strong>[JUN. 2023]</strong> Secondment at the institute <a href="https://www.imm.cnr.it/">CNR-IMM</a>, in collarboartion with professor <span style="color:#e74d3c"><a href="https://www.mdm.imm.cnr.it/users/lamperti-alessio">Alessio Lamperti.</a></span></li>
<li><strong>[DEC. 2022]</strong> Secondment at the  <a href="https://www.aalto.fi/en/department-of-applied-physics">department Applied Physics of Aalto University</a>, in collarboartion with professor <span style="color:#e74d3c"><a href="https://www.aalto.fi/en/people/sebastiaan-van-dijken">Sebastiaan van Dijken.</a></span></li>
<li><strong>[JUN. 2022]</strong> Secondment at the  <a href="https://www.aalto.fi/en/department-of-applied-physics">department Applied Physics of Aalto University</a>, in collarboartion with professor <span style="color:#e74d3c"><a href="https://www.aalto.fi/en/people/sebastiaan-van-dijken">Sebastiaan van Dijken.</a></span></li>
<li><strong>[JUN. 2021]</strong> Join the <a href="https://www.spin-ion.com/">Spin-Ion Technologies</a>, involved in the <a href="https://bemagic-etn.eu/">BeMAGIC</a> program (Marie Sklodowska-Curie European Training Network).</li>
 -->
</div>
</ul>


