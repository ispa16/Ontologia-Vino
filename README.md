
<style>
 /* define a class "noprint" for sections which don't get printed */  
.noprint { display: none; }

/* our syntax menu for switching */
div.syntaxmenu {
  border: 1px dotted black;
  padding:0.5em;
  margin: 1em; 
}

.container {
    margin-right: auto;
    margin-left: auto;
    padding-left: 15px;
    padding-right: 15px;
}

@media print {
   div.syntaxmenu { display:none; }
}

/* use tab-like headers for syntax examples */
div.exampleheader {
  font-size: 90%;
  float: left;
  background: #F9F9F9;
  color: #2F6FAB;
  border: 1px dashed #2F6FAB;
  border-bottom: 0px;
  padding-top: 2px;
}

div.exampleheader span.exampleheader {
  background: #F9F9F9;
  padding-top: 0px;
  padding-right: 10px;
  padding-left: 10px;
  padding-bottom: 3px;
  padding-top: 0px;
}

/* Also copy MediaWiki style here, so it will not look different when exported */
div.fssyntax pre, div.rdfxml pre, div.owlxml pre, div.turtle pre, div.manchester pre  {
  background-color: #F9F9F9;
  border: 1px dashed #2F6FAB;
  color: black;
  line-height: 1.1em;
  padding: 1em;
  clear: both;
  margin-left: 0em;
}
/* Expansion to add the status*/
.status {
    position: fixed;
    left: 0em;
    top: 0em;
    text-align: right;
    vertical-align: middle;
    /* Square version of the inside span. Slightly larger */
    width: 26em;
    height: 26em;
    z-index: -1;
    opacity: 0.8;
    
    /** From http://stackoverflow.com/questions/1080792/how-to-draw-vertical-text-with-css-cross-browser */

    -webkit-transform: rotate(-90deg);
    -moz-transform: rotate(-90deg);
    -ms-transform: rotate(-90deg);
    -o-transform: rotate(-90deg);
    transform: rotate(-90deg);
    /* also accepts left, right, top, bottom coordinates; not
    * required, but a good idea for styling */
    -webkit-transform-origin: 50% 50%;
    -moz-transform-origin: 50% 50%;
    -ms-transform-origin: 50% 50%;
    -o-transform-origin: 50% 50%;
    transform-origin: 50% 50%;

    /* Should be unset in IE9+ I think. */
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
}

/* The actual status box */
 .status div {   
    display: block;
    background: rgb(0, 90, 156);
    color: white;
    width: 24em;
    padding-top: 0.3em;
    padding-left: 0em;
    padding-right: 5em;
    padding-bottom: 0.3em;
    /* Enable for debugging 
    border: red thin solid;
     */
} 

/* And text inside, don't confuse fonts as it breaks em above */
.status div span {
    font-family: "Tauri";
    font-size: larger;
}
 </style>

<body>
<div class="container">
<div class="head">
<div style="float:right">language <a href="index-en.html"><b>en</b></a> </div>


<dl>
<dt>This version:</dt>
<dd><a href="v.1">v.1</a></dd>
<dt>Latest version:</dt>
<dd><a href="[Ontology URI]">[Ontology URI]</a></dd>
<dt>Download serialization:</dt><dd><span><a href="ontology.jsonld" target="_blank"><img src="https://img.shields.io/badge/Format-JSON_LD-blue.svg" alt="JSON-LD" /></a> </span><span><a href="ontology.rdf" target="_blank"><img src="https://img.shields.io/badge/Format-RDF/XML-blue.svg" alt="RDF/XML" /></a> </span><span><a href="ontology.nt" target="_blank"><img src="https://img.shields.io/badge/Format-N_Triples-blue.svg" alt="N-Triples" /></a> </span><span><a href="ontology.ttl" target="_blank"><img src="https://img.shields.io/badge/Format-TTL-blue.svg" alt="TTL" /></a> </span></dd><dt>License:</dt><dd><a href="http://insertlicenseURIhere.org" target="_blank"><img src="https://img.shields.io/badge/License-license%20name%20goes%20here-blue.svg" alt="http://insertlicenseURIhere.org" /></a>
</dd><dt>Visualization:</dt><dd><a href="webvowl/index.html#" target="_blank"><img src="https://img.shields.io/badge/Visualize_with-WebVowl-blue.svg" alt="Visualize with WebVowl" /></a></dd>
<!-- <dt>Evaluation:</dt><dd><a href="OOPSEvaluation/oopsEval.html#" target="_blank"><img src="https://img.shields.io/badge/Evaluate_with-OOPS! (OntOlogy Pitfall Scanner!)-blue.svg" alt="Evaluate with OOPS!" /></a></dd> --></dl>

<a href="provenance/provenance-en.html" target="_blank">Provenance of this page</a><hr/>
</div>
<div class="status">
<div>
<span>Ontology Specification Draft</span>
</div>
</div>     <div id="abstract"><h2>Abstract</h2><span class="markdown">
This is a placeholder text for the abstract. The abstract should contain a couple of sentences summarizing the ontology and its purpose.</span>
</div>
<div id="toc"></div> 

<!--INTRODUCTION SECTION-->
    <div id="introduction"><h2 id="intro" class="list">Introduction <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<span class="markdown">
This is a place holder text for the introduction. The introduction should briefly describe the ontology, its motivation, state of the art and goals.</span>
<div id="namespacedeclarations">
<h3 id="ns" class="list">Namespace declarations</h3>
<div id="ns" align="center">
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
<span class="markdown">
This ontology has the following classes and properties.</span>
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
</ul><iframe align="center" width="100%" height ="500px" src="webvowl/index.html"></iframe> 
</div>
  

<!--DESCRIPTION SECTION-->
    <div id="description"><h2 id="desc" class="list">Wine Ontology: Description <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<span class="markdown">
This is a placeholder text for the description of your ontology. The description should include an explanation and a diagram explaining how the classes are related, examples of usage, etc.</span>

</div>
   

<!--CROSSREF SECTION-->
   <div id="crossref"><h2 id="crossreference" class="list">Cross-reference for Wine Ontology classes, object properties and data properties <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
This section provides details for each class and property defined by Wine Ontology.
<div xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
     id="annotationproperties">
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
<div   class="entity">
</div>
</div>
</div>
    

<!--REFERENCES SECTION-->
  <div id="references">
<h2 id="ref" class="list">References <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<span class="markdown">
Add your references here. It is recommended to have them as a list.</span>

</div>
<div id="acknowledgments">
<h2 id="ack" class="list">Acknowledgments <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<p>
The authors would like to thank <a href="http://www.essepuntato.it/">Silvio Peroni</a> for developing <a href="http://www.essepuntato.it/lode">LODE</a>, a Live OWL Documentation Environment, which is used for representing the Cross Referencing Section of this document and <a href="https://w3id.org/people/dgarijo">Daniel Garijo</a> for developing <a href="https://github.com/dgarijo/Widoco">Widoco</a>, the program used to create the template used in this documentation.</p>
</div>


</div>
</body>
</html>
