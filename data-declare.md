# Internal Tables

## Old Syntax
<pre><code class="language-abap">
DATA: lt_tab TYPE TABLE OF string.
APPEND 'Hello' TO lt_tab.
</code></pre>

## New Syntax
<pre><code class="language-abap">
DATA(lt_tab) = VALUE stringtab( ( 'Hello' ) ).
</code></pre>

