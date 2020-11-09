<!--
  accepted: @width @align p br table tr td q sup sub h1 h2 h3 h4 h5 h6 samp kbd
  rejected: @style @class @data colgroup col font small big dfn center svg
  useless: table@width table@border table@frame table@rules

  h3: 1.25em bold bottom16px top24px
  h4: 1em bold bottom16px top24px
  p: 1em bottom16px

  use sup/sub as small or to fine-tine spacing (can be nested)
-->

<table>
  <tr>
    <!--
      stylesheet has table{width:max-content;max-width:100%}
      so use td@width=9999999 over table@width=100%
    -->
    <td bgcolor="blue" colspan="2" width="9999999" align="center">
      <h1><samp>
        <a href="https://www.azabani.com/">~</a>
        : <a href="https://www.azabani.com/about/">~/about/</a>
        : <a href="https://www.azabani.com/labs/">~/labs/</a>
        : <a href="https://bitbucket.org/delan">bitbucket</a>
        : <a href="https://twitter.com/dazabani">@dazabani</a>
      </samp></h1>
  <tr>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/matrix86">matrix86</a></b><br>
      <sub>cmatrix clone in three eighths of a PC MBR<br>x86 (nasm)</sub>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/badapple.rs">badapple.rs</a></b><br>
      <sub>Bad Apple!! for taskmgr<br>Rust</sub>
  <tr>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/ing2ynab">ing2ynab</a></b><br>
      <sub>cleans up ing.com.au transactions for YNAB<br>Rust</sub>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/daria.daz.cat">daria.daz.cat</a></b><br>
      <sub>root overlay for my home router<br>POSIX sh</sub>
</table>
