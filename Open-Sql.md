# Open Sql

## Open Sql Table Old Syntax
<pre><code class="language-abap">
DATA: lt_data type table of sfligt.
  Select * 
     from sflight
  into table lt_data.
</code></pre>

## Open Sql Table New Syntax
<pre><code class="language-abap">
  Select * 
     from sflight
  into table @data(lt_data).
</code></pre>

## Open Sql Str Old Syntax
<pre><code class="language-abap">
DATA: ls_data type sfligt.
  Select single * 
     from sflight
  into  ls_data.
</code></pre>

## Open Sql Table New Syntax
<pre><code class="language-abap">
  Select single * 
     from sflight
  into @data(ls_data).
</code></pre>

