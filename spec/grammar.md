---
layout: dev
title: Clinical Quality Language Grammar
standards-status: normative
---

This page contains the [Antlr 4.0](http://www.antlr.org/) grammar for Clinical Quality Language.

For a visual representation of the syntax of CQL, refer to [Appendix L - CQL Syntax Diagrams](19-l-cqlsyntaxdiagrams.html).

<a id="cql" href="cql/cql.g4">Raw CQL grammar</a>

<pre>
{% include_relative cql/cql.g4 %}
</pre>

----
NOTE: CQL extends from the FHIRPath grammar, and so uses the core production rules defined there. The FHIRPath grammar is included here for reference only, the FHIRPath grammar below is part of the FHIRPath specification.
----

<a id="fhirpath" href="cql/fhirpath.g4">Raw FHIRPath grammar</a>

<pre>
{% include_relative cql/fhirpath.g4 %}
</pre>
