<body title="X is 1412 and Y is 539">
<div class="container" title="X is 1391 and Y is 573">
<div class="head">
<div style="float:right">language <a href="index-en.html"><b>en</b></a> </div>


<dl>
<dt>This version:</dt>
<dd><a href="v.1">v.1</a></dd>
<dt>Latest version:</dt>
<dd><a href="[Ontology URI]">[Ontology URI]</a></dd>
<dt>Download serialization:</dt><dd><span><a href="ontology.jsonld" target="_blank"><img src="https://img.shields.io/badge/Format-JSON_LD-blue.svg" alt="JSON-LD"></a> </span><span><a href="ontology.rdf" target="_blank"><img src="https://img.shields.io/badge/Format-RDF/XML-blue.svg" alt="RDF/XML"></a> </span><span><a href="ontology.nt" target="_blank"><img src="https://img.shields.io/badge/Format-N_Triples-blue.svg" alt="N-Triples"></a> </span><span><a href="ontology.ttl" target="_blank"><img src="https://img.shields.io/badge/Format-TTL-blue.svg" alt="TTL"></a> </span></dd><dt>License:</dt><dd><a href="http://insertlicenseURIhere.org" target="_blank"><img src="https://img.shields.io/badge/License-license%20name%20goes%20here-blue.svg" alt="http://insertlicenseURIhere.org"></a>
</dd><dt>Visualization:</dt><dd><a href="webvowl/index.html#" target="_blank"><img src="https://img.shields.io/badge/Visualize_with-WebVowl-blue.svg" alt="Visualize with WebVowl"></a></dd>
<!-- <dt>Evaluation:</dt><dd><a href="OOPSEvaluation/oopsEval.html#" target="_blank"><img src="https://img.shields.io/badge/Evaluate_with-OOPS! (OntOlogy Pitfall Scanner!)-blue.svg" alt="Evaluate with OOPS!" /></a></dd> --></dl>

<a href="provenance/provenance-en.html" target="_blank">Provenance of this page</a><hr>
</div>
<div class="status">
<div>
<span>Ontology Specification Draft</span>
</div>
</div>     <div id="abstract"><h2>Abstract</h2><p>This is a placeholder text for the abstract. The abstract should contain a couple of sentences summarizing the ontology and its purpose.</p>

</div>
<div id="toc"><h2>Table of contents</h2><ul><li>1. <a href="#intro">Introduction </a></li><ul><li>1.1. <a href="#ns">Namespace declarations</a></li></ul><li>2. <a href="#overv">Wine Ontology: Overview </a></li><li>3. <a href="#desc">Wine Ontology: Description </a></li><li>4. <a href="#crossreference">Cross-reference for Wine Ontology classes, object properties and data properties </a></li><ul><li>4.1. <a href="#annotationproperties">Annotation Properties</a></li></ul><li title="X is 1380 and Y is 590">5. <a href="#ref">References </a></li><li title="X is 1371 and Y is 606">6. <a href="#ack">Acknowledgments </a></li></ul></div> 

<!--INTRODUCTION SECTION-->
    <div id="introduction" title="X is 1315 and Y is 687"><h2 id="intro" class="list" title="X is 1322 and Y is 677">Introduction <span class="backlink" title="X is 1337 and Y is 657"> back to <a href="#toc">ToC</a></span></h2>
<p title="X is 1309 and Y is 698">This is a place holder text for the introduction. The introduction should briefly describe the ontology, its motivation, state of the art and goals.</p>

<div id="namespacedeclarations" title="X is 1266 and Y is 766">
<h3 id="ns" class="list" title="X is 1283 and Y is 736">Namespace declarations</h3>
<div id="ns" align="center" title="X is 1252 and Y is 790">
<table>
<caption> <a href="#ns"> Table 1</a>: Namespaces used in the document </caption>
<tbody>
<tr><td><b>wn</b></td><td>&lt;URI&gt;</td></tr>
<tr><td></td><td></td></tr>
<tr><td><b>dbo</b></td><td>&lt;http://dbpedia.org/ontology&gt;</td></tr>
<tr><td><b>schema</b></td><td>&lt;http://schema.org&gt;</td></tr>
<tr><td><b>[Ontology NS Prefix]</b></td><td>&lt;http://sbc.utpl.edu.ec/wines-food-data&gt;</td></tr>
<tr><td><b>owl</b></td><td>&lt;http://www.w3.org/2002/07/owl&gt;</td></tr>
<tr><td><b>rdf</b></td><td>&lt;http://www.w3.org/1999/02/22-rdf-syntax-ns&gt;</td></tr>
<tr><td><b>xml</b></td><td>&lt;http://www.w3.org/XML/1998/namespace&gt;</td></tr>
<tr><td><b>xsd</b></td><td>&lt;http://www.w3.org/2001/XMLSchema&gt;</td></tr>
<tr><td><b>rdfs</b></td><td>&lt;http://www.w3.org/2000/01/rdf-schema&gt;</td></tr>
<tr><td><b>foaf</b></td><td>&lt;http://xmlns.com/foaf/0.1&gt;</td></tr>
</tbody>
</table>
</div>
</div>
</div>
  

<!--OVERVIEW SECTION-->
    <div id="overview"><h2 id="overv" class="list">Wine Ontology: Overview <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<p>This ontology has the following classes and properties.</p>

<h4>Annotation Properties</h4><ul xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" class="hlist">
   <li>
      <a href="#http://dbpedia.org/ontology/Country" title="http://dbpedia.org/ontology/Country">
         <span>country</span>
      </a>
   </li>
   <li>
      <a href="#http://dbpedia.org/ontology/Grape_List" title="http://dbpedia.org/ontology/Grape_List">
         <span>grape list</span>
      </a>
   </li>
   <li>
      <a href="#http://dbpedia.org/ontology/Manufacturer" title="http://dbpedia.org/ontology/Manufacturer">
         <span>manufacturer</span>
      </a>
   </li>
   <li>
      <a href="#http://schema.org/name" title="http://schema.org/name">
         <span>name</span>
      </a>
   </li>
   <li>
      <a href="#http://sbc.utpl.edu.ec/wines-food-data/price" title="http://sbc.utpl.edu.ec/wines-food-data/price">
         <span>price</span>
      </a>
   </li>
   <li>
      <a href="#http://dbpedia.org/ontology/Province" title="http://dbpedia.org/ontology/Province">
         <span>province</span>
      </a>
   </li>
   <li>
      <a href="#http://dbpedia.org/ontology/Region" title="http://dbpedia.org/ontology/Region">
         <span>region</span>
      </a>
   </li>
</ul><iframe align="center" width="100%" height="500px" src="webvowl/index.html"></iframe> 
</div>
  

<!--DESCRIPTION SECTION-->
    <div id="description"><h2 id="desc" class="list">Wine Ontology: Description <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<p>This is a placeholder text for the description of your ontology. The description should include an explanation and a diagram explaining how the classes are related, examples of usage, etc.</p>


</div>
   

<!--CROSSREF SECTION-->
   <div id="crossref"><h2 id="crossreference" class="list">Cross-reference for Wine Ontology classes, object properties and data properties <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
This section provides details for each class and property defined by Wine Ontology.
<div xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" id="annotationproperties">
   <h3 id="annotationproperties" class="list">Annotation Properties</h3>
   <ul class="hlist">
      <li>
         <a href="#http://dbpedia.org/ontology/Country" title="http://dbpedia.org/ontology/Country">
            <span>country</span>
         </a>
      </li>
      <li>
         <a href="#http://dbpedia.org/ontology/Grape_List" title="http://dbpedia.org/ontology/Grape_List">
            <span>grape list</span>
         </a>
      </li>
      <li>
         <a href="#http://dbpedia.org/ontology/Manufacturer" title="http://dbpedia.org/ontology/Manufacturer">
            <span>manufacturer</span>
         </a>
      </li>
      <li>
         <a href="#http://schema.org/name" title="http://schema.org/name">
            <span>name</span>
         </a>
      </li>
      <li>
         <a href="#http://sbc.utpl.edu.ec/wines-food-data/price" title="http://sbc.utpl.edu.ec/wines-food-data/price">
            <span>price</span>
         </a>
      </li>
      <li>
         <a href="#http://dbpedia.org/ontology/Province" title="http://dbpedia.org/ontology/Province">
            <span>province</span>
         </a>
      </li>
      <li>
         <a href="#http://dbpedia.org/ontology/Region" title="http://dbpedia.org/ontology/Region">
            <span>region</span>
         </a>
      </li>
   </ul>
   <div class="entity" id="http://dbpedia.org/ontology/Country">
      <h3>country<sup class="type-ap" title="annotation property">ap</sup>
         <span class="backlink"> back to <a href="#toc">ToC</a> or <a href="#annotationproperties">Annotation Property ToC</a>
         </span>
      </h3>
      <p>
         <strong>IRI:</strong> http://dbpedia.org/ontology/Country</p>
   </div>
   <div class="entity" id="http://dbpedia.org/ontology/Grape_List">
      <h3>grape list<sup class="type-ap" title="annotation property">ap</sup>
         <span class="backlink"> back to <a href="#toc">ToC</a> or <a href="#annotationproperties">Annotation Property ToC</a>
         </span>
      </h3>
      <p>
         <strong>IRI:</strong> http://dbpedia.org/ontology/Grape_List</p>
   </div>
   <div class="entity" id="http://dbpedia.org/ontology/Manufacturer">
      <h3>manufacturer<sup class="type-ap" title="annotation property">ap</sup>
         <span class="backlink"> back to <a href="#toc">ToC</a> or <a href="#annotationproperties">Annotation Property ToC</a>
         </span>
      </h3>
      <p>
         <strong>IRI:</strong> http://dbpedia.org/ontology/Manufacturer</p>
   </div>
   <div class="entity" id="http://schema.org/name">
      <h3>name<sup class="type-ap" title="annotation property">ap</sup>
         <span class="backlink"> back to <a href="#toc">ToC</a> or <a href="#annotationproperties">Annotation Property ToC</a>
         </span>
      </h3>
      <p>
         <strong>IRI:</strong> http://schema.org/name</p>
   </div>
   <div class="entity" id="http://sbc.utpl.edu.ec/wines-food-data/price">
      <h3>price<sup class="type-ap" title="annotation property">ap</sup>
         <span class="backlink"> back to <a href="#toc">ToC</a> or <a href="#annotationproperties">Annotation Property ToC</a>
         </span>
      </h3>
      <p>
         <strong>IRI:</strong> http://sbc.utpl.edu.ec/wines-food-data/price</p>
   </div>
   <div class="entity" id="http://dbpedia.org/ontology/Province">
      <h3>province<sup class="type-ap" title="annotation property">ap</sup>
         <span class="backlink"> back to <a href="#toc">ToC</a> or <a href="#annotationproperties">Annotation Property ToC</a>
         </span>
      </h3>
      <p>
         <strong>IRI:</strong> http://dbpedia.org/ontology/Province</p>
   </div>
   <div class="entity" id="http://dbpedia.org/ontology/Region">
      <h3>region<sup class="type-ap" title="annotation property">ap</sup>
         <span class="backlink"> back to <a href="#toc">ToC</a> or <a href="#annotationproperties">Annotation Property ToC</a>
         </span>
      </h3>
      <p>
         <strong>IRI:</strong> http://dbpedia.org/ontology/Region</p>
   </div>
</div><div id="legend">
<h2>Legend <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<div class="entity">
</div>
</div>
</div>
    

<!--REFERENCES SECTION-->
  <div id="references">
<h2 id="ref" class="list">References <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<p>Add your references here. It is recommended to have them as a list.</p>


</div>
<div id="acknowledgments">
<h2 id="ack" class="list">Acknowledgments <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<p>
The authors would like to thank <a href="http://www.essepuntato.it/">Silvio Peroni</a> for developing <a href="http://www.essepuntato.it/lode">LODE</a>, a Live OWL Documentation Environment, which is used for representing the Cross Referencing Section of this document and <a href="https://w3id.org/people/dgarijo">Daniel Garijo</a> for developing <a href="https://github.com/dgarijo/Widoco">Widoco</a>, the program used to create the template used in this documentation.</p>
</div>


</div>

</body>
