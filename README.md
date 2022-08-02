<html>
<head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8" />
 <link rel="stylesheet" href="resources/primer.css" media="screen" />    <link rel="stylesheet" href="resources/rec.css" media="screen" />    <link rel="stylesheet" href="resources/extra.css" media="screen" />    <link rel="stylesheet" href="resources/owl.css" media="screen" />    <title>Ontology Documentation generated by WIDOCO</title>


<!-- SCHEMA.ORG METADATA -->
<script type="application/ld+json">{"@context":"https://schema.org","@type":"TechArticle","url":"http://www.semanticweb.org/georg/ontologies/2022/3/WOOD","image":"http://vowl.visualdataweb.org/webvowl/#iri=http://www.semanticweb.org/georg/ontologies/2022/3/WOOD","name":"http://www.semanticweb.org/georg/ontologies/2022/3/WOOD", "headline":"This Ontology helps to define wood damages in the field of construction. Experts in wood damages can use this ontology for writing reports. It is a sub-ontology to the "Damage Topology Ontology" and is defined as an "Classified damage". It defines damage types, connected causes, repair methods and investigation procedures. All these categories are part of the Report.", "datePublished":"13.07.2022", "license":"https://creativecommons.org/licenses/by/2.0/", "author":[{"@type":"Person","name":"Georg V"}]}</script>

<script src="resources/jquery.js"></script> 
<script src="resources/marked.min.js"></script> 
    <script> 
function loadHash() {
  jQuery(".markdown").each(function(el){jQuery(this).after(marked(jQuery(this).text())).remove()});
	var hash = location.hash;
	if($(hash).offset()!=null){
	  $('html, body').animate({scrollTop: $(hash).offset().top}, 0);
}
	loadTOC();
}
function loadTOC(){
	//process toc dynamically
	  var t='<h2>Table of contents</h2><ul>';i = 1;j=0;
	  jQuery(".list").each(function(){
		if(jQuery(this).is('h2')){
			if(j>0){
				t+='</ul>';
				j=0;
			}
			t+= '<li>'+i+'. <a href=#'+ jQuery(this).attr('id')+'>'+ jQuery(this).ignore("span").text()+'</a></li>';
			i++;
		}
		if(jQuery(this).is('h3')){
			if(j==0){
				t+='<ul>';
			}
			j++;
			t+= '<li>'+(i-1)+'.'+j+'. '+'<a href=#'+ jQuery(this).attr('id')+'>'+ jQuery(this).ignore("span").text()+'</a></li>';
		}
	  });
	  t+='</ul>';
	  $("#toc").html(t); 
}
 $.fn.ignore = function(sel){
        return this.clone().find(sel||">*").remove().end();
 };    $(function(){
      $("#abstract").load("sections/abstract-en.html"); 
      $("#introduction").load("sections/introduction-en.html"); 
      $("#overview").load("sections/overview-en.html"); 
      $("#description").load("sections/description-en.html"); 
      $("#references").load("sections/references-en.html"); 
      $("#crossref").load("sections/crossref-en.html", null, loadHash); 
    });
    </script> 
  </head> 

<body>
<div class="container">
<div class="head">
<div style="float:right">language <a href="index-en.html"><b>en</b></a> </div>
<h2>Release 13.07.2022</h2>


<dl>
<dt>Latest version:</dt>
<dd><a href="http://www.semanticweb.org/georg/ontologies/2022/3/WOOD">http://www.semanticweb.org/georg/ontologies/2022/3/WOOD</a></dd>
<dt>Authors:</dt>
<dd>Georg V</dd>

<dt>Download serialization:</dt><dd><span><a href="ontology.jsonld" target="_blank"><img src="https://img.shields.io/badge/Format-JSON_LD-blue.svg" alt="JSON-LD" /></a> </span><span><a href="ontology.rdf" target="_blank"><img src="https://img.shields.io/badge/Format-RDF/XML-blue.svg" alt="RDF/XML" /></a> </span><span><a href="ontology.nt" target="_blank"><img src="https://img.shields.io/badge/Format-N_Triples-blue.svg" alt="N-Triples" /></a> </span><span><a href="ontology.ttl" target="_blank"><img src="https://img.shields.io/badge/Format-TTL-blue.svg" alt="TTL" /></a> </span></dd><dt>License:</dt><dd><a href="https://creativecommons.org/licenses/by/2.0/" target="_blank"><img src="https://img.shields.io/badge/License-https://creativecommons.org/licenses/by/2.0/-blue.svg" alt="https://creativecommons.org/licenses/by/2.0/" /></a>
</dd><dt>Visualization:</dt><dd><a href="webvowl/index.html#" target="_blank"><img src="https://img.shields.io/badge/Visualize_with-WebVowl-blue.svg" alt="Visualize with WebVowl" /></a></dd>
<!-- <dt>Evaluation:</dt><dd><a href="OOPSEvaluation/oopsEval.html#" target="_blank"><img src="https://img.shields.io/badge/Evaluate_with-OOPS! (OntOlogy Pitfall Scanner!)-blue.svg" alt="Evaluate with OOPS!" /></a></dd> --><dt>Cite as:</dt>
<dd>Georg V.</dd>
</dl>

<hr/>
</div>
<div class="status">
<div>
<span>Ontology Specification Draft</span>
</div>
</div>     <div id="abstract"></div>
<div id="toc"></div>     <div id="introduction"></div>
     <div id="overview"></div>
     <div id="description"></div>
     <div id="crossref"></div>
     <div id="references"></div>
<div id="acknowledgments">
<h2 id="ack" class="list">Acknowledgments <span class="backlink"> back to <a href="#toc">ToC</a></span></h2>
<p>
This research is part of the Master Thesis at the Design Computation Chair of the RWTH Aachen. <br>
<br>
The authors would like to thank <a href="http://www.essepuntato.it/">Silvio Peroni</a> for developing <a href="http://www.essepuntato.it/lode">LODE</a>, a Live OWL Documentation Environment, which is used for representing the Cross Referencing Section of this document and <a href="https://w3id.org/people/dgarijo">Daniel Garijo</a> for developing <a href="https://github.com/dgarijo/Widoco">Widoco</a>, the program used to create the template used in this documentation.</p>
</div>


</div>
</body>
</html>
