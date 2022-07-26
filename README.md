<body>
<div class="container">
<div class="head">


<dl>
<dt>&Uacute;ltima Versi&oacute;n:</dt>
<dd><a href="Uri">Uri</a></dd>
<dt>Descargar serializaci&oacute;n:</dt><dd><span><a href="ontology.jsonld" target="_blank"><img src="https://img.shields.io/badge/Format-JSON_LD-blue.svg" alt="JSON-LD" /></a> </span><span><a href="ontology.rdf" target="_blank"><img src="https://img.shields.io/badge/Format-RDF/XML-blue.svg" alt="RDF/XML" /></a> </span><span><a href="ontology.nt" target="_blank"><img src="https://img.shields.io/badge/Format-N_Triples-blue.svg" alt="N-Triples" /></a> </span><span><a href="ontology.ttl" target="_blank"><img src="https://img.shields.io/badge/Format-TTL-blue.svg" alt="TTL" /></a> </span></dd><dt>Licencia:</dt><dd><a href="http://tituloLicenciaSeleccionado.org" target="_blank"><img src="https://img.shields.io/badge/License-Insertar%20el%20t&iacute;tulo%20de%20la%20licencia%20aqu&iacute-blue.svg" alt="http://tituloLicenciaSeleccionado.org" /></a>
</dd><dt>Visualizaci&oacute;n:</dt><dd><a href="webvowl/index.html#" target="_blank"><img src="https://img.shields.io/badge/Visualize_with-WebVowl-blue.svg" alt="Visualize with WebVowl" /></a></dd>
<!-- <dt>Evaluation:</dt><dd><a href="OOPSEvaluation/oopsEval.html#" target="_blank"><img src="https://img.shields.io/badge/Evaluate_with-OOPS! (OntOlogy Pitfall Scanner!)-blue.svg" alt="Evaluate with OOPS!" /></a></dd> --></dl>

<a href="provenance/provenance-es.html" target="_blank">Provenance de esta p&aacute;gina</a><hr/>
</div>
<div class="status">
<div>
<span>Especificacion de Ontologia</span>
</div>
</div>     <div id="abstract"><h2>S&iacute;ntesis</h2><span class="markdown">
El propósito de esta ontología es dar a conocer las diferentes combinaciones que existen entre los vinos y las comidas para poder disfrutar de una mejor manera estas mismas.</span>
</div>
<div id="toc"></div> 

<!--INTRODUCTION SECTION-->
<h3 id="ns" class="list">Introducci&oacute;n de namespaces</h3>   
<span class="markdown">Este vocabulario representa la información de vinos y comidas, lo cual comprende los distintos tipos de vino y excluye otro tipo de bebidas.

Por tanto se define el alcance de este vocabulario en:

vino, uva, bodega, ubicación, color, cuerpo, sabor y contenido de azúcar de un vino; diferentes tipos de alimentos, como pescado y carne roja; subtipos de vino como el vino blanco.</span>
<div id="namespacedeclarations">
<h3 id="ns" class="list">Declaraci&oacute;n de namespaces</h3>
<div id="ns" align="center">
<table>
<caption> <a href="#ns"> Tabla 1</a>: Namespaces utilizados en el documento </caption>
<tbody>
<tr><td><b>wn</b></td><td>&lt;Uri&gt;</td></tr>
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
   
 <h3 id="ns" class="list">Vino: Resumen </h3>   
<span class="markdown">La ontolog&iacute;a se compone de las siguientes clases y propiedades:</span>
<h4>Propiedades usadas para anotaci&oacute;n</h4><ul xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" class="hlist">
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
</div>
  

<!--DESCRIPTION SECTION-->
<div id="description"><h2 id="desc" class="list">Vino: Descripci&oacute;n </h2>
<span class="markdown">Descripci&oacute;n completa de la ontolog&iacute;a: en caso de ser posible, a&ntilde;adir un diagrama explicando c&oacute;omo las clases est&aacute;n relacionadas, ejemplos de uso, etc.</span>

</div>
   

<!--CROSSREF SECTION-->
   <div id="crossref"><h2 id="crossreference" class="list">T&eacute;rminos de Vino para clases, propiedades de objeto y propiedades de datos </h2>
Esta secci&oacute;n introduce m&aacute;s detalles sobre cada clase y propiedad definida por Vino.
<div xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
     id="annotationproperties">
   <h2>Propiedades de anotación</h2>
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
<h3>country<sup class="type-ap" title="propiedad de anotación">ap</sup>
</span>
</h3>
<p>
<strong>IRI:</strong> http://dbpedia.org/ontology/Country</p>
</div>
<div class="entity" id="http://dbpedia.org/ontology/Grape_List">
<h3>grape list<sup class="type-ap" title="propiedad de anotación">ap</sup>

</span>
</h3>
<p>
<strong>IRI:</strong> http://dbpedia.org/ontology/Grape_List</p>
</div>
<div class="entity" id="http://dbpedia.org/ontology/Manufacturer">
<h3>manufacturer<sup class="type-ap" title="propiedad de anotación">ap</sup>

</span>
</h3>
<p>
<strong>IRI:</strong> http://dbpedia.org/ontology/Manufacturer</p>
</div>
<div class="entity" id="http://schema.org/name">
<h3>name<sup class="type-ap" title="propiedad de anotación">ap</sup>

</span>
</h3>
<p>
<strong>IRI:</strong> http://schema.org/name</p>
</div>
<div class="entity" id="http://sbc.utpl.edu.ec/wines-food-data/price">
<h3>price<sup class="type-ap" title="propiedad de anotación">ap</sup>

</span>
</h3>
<p>
<strong>IRI:</strong> http://sbc.utpl.edu.ec/wines-food-data/price</p>
</div>
<div class="entity" id="http://dbpedia.org/ontology/Province">
<h3>province<sup class="type-ap" title="propiedad de anotación">ap</sup>

</span>
</h3>
<p>
<strong>IRI:</strong> http://dbpedia.org/ontology/Province</p>
</div>
<div class="entity" id="http://dbpedia.org/ontology/Region">
<h3>region<sup class="type-ap" title="propiedad de anotación">ap</sup>
</span>
</h3>
<p>
<strong>IRI:</strong> http://dbpedia.org/ontology/Region</p>
</div>
</div><div id="legend">
<div   class="entity">
</div>
</div>
</div>
    

<!--REFERENCES SECTION-->
<div id="references">
<h3 id="ns" class="list">Referencias</h3>   
    <br> *Aguado-De Cea, G., Montiel-Ponsoda, E., Poveda-Villalón, M., and Giraldo-Pasmin, O.X. (2015). Lexicalizing Ontologies: The issues behind the labels. In Multimodal communication in the 21st century: Professional and academic challenges. 33rd Conference of the Spanish Association of Applied Linguistics (AESLA), XXXIII AESLA.
<br> *Noy, N. F., McGuinness, D. L., et al. (2001). Ontology development 101: A guide to creating your first ontology.
<br> *Gómez-Pérez, A. (1999). Evaluation of Taxonomic Knowledge in Ontologies and Knowledge Bases. Proceedings of the Banff Knowledge Acquisition for Knowledge-Based Systems Workshop. Alberta, Canada.
<br> *Montiel-Ponsoda, E., Vila Suero, D., Villazón-Terrazas, B., Dunsire, G., Escolano Rodríguez, E., Gómez-Pérez, A. (2011). Style guidelines for naming and labeling ontologies in the multilingual web.
<br> *Vrandecic, D. (2010). Ontology Evaluation. PhD thesis.
<br> *Gómez-Pérez, A. (2004). Ontology evaluation. In Handbook on ontologies, pages 251-273. Springer.
<br> *Rector, A., Drummond, N., Horridge, M., Rogers, J., Knublauch, H., Stevens, R., Wang, H., and Wroe, C. (2004). Owl pizzas: Practical experience of teaching owl-dl: Common errors & common patterns. In Engineering Knowledge in the Age of the Semantic Web, pages 63-81. Springer.
<br> *Hogan, A., Harth, A., Passant, A., Decker, S., and Polleres, A. (2010). Weaving the pedantic web. In Proceedings of the WWW2010 Workshop on Linked Data on the Web, LDOW 2010, Raleigh, USA, April 27, 2010.
<br> *Archer, P., Goedertier, S., and Loutas, N. (2012). D7. 1.3-study on persistent URIs, with identification of best practices and recommendations on the topic for the Mss and the EC. PwC EU Services.
<br> *Bernes-Lee Tim. (2006). “Linked Data - Design issues”. http://www.w3.org/DesignIssues/LinkedData.html
<br> *Heath, T. and Bizer, C. (2011). Linked Data: Evolving the Web into a Global Data Space. Morgan & Claypool, 1st edition.
<br> *Vatant, B. (2012). Is your linked data vocabulary 5-star?. http://bvatant.blogspot.fr/2012/02/is-your-linked-data-vocabulary-5-star_9588.html

</div>
<div id="acknowledgments">
<p>Los autores agradecen a <a href="http://www.essepuntato.it/">Silvio Peroni</a> el desarrollo de <a href="http://www.essepuntato.it/lode">LODE</a>, un entorno de documentaci&oacute;n para OWL que es usado para generar la descripci&oacute;n de t&eacute;rminos de la ontolog&iacute;a de este documento; y a  <a href="http://purl.org/net/dgarijo">Daniel Garijo</a> por desarrollar <a href="https://github.com/dgarijo/Widoco">Widoco</a>, el programa utilizado para producir la plantilla en la que se basa este documento.</p>
</div>


</div>
</body>
