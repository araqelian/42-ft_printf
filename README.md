# 🗣 Subject &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ft_printf

<br>
<table>
  <tr>
    <td>Program &nbsp;name</td>
    <td>libftprintf.a</td>
  </tr>
  <tr>
    <td>Turn &nbsp;in &nbsp;files</td>
    <td>Makefile, &nbsp;*.h,&nbsp; */*.h, &nbsp;*.c,&nbsp; */*.c</td>
  </tr>
  <tr>
    <td>Makefile</td>
    <td>NAME, &nbsp;all,&nbsp; clean, &nbsp;fclean, &nbsp;re</td>
  </tr>
  <tr>
    <td>External &nbsp;functs.</td>
    <td>malloc, &nbsp;free, &nbsp;write, &nbsp;va_start,&nbsp; va_arg,&nbsp; va_copy,&nbsp; va_end</td>
  </tr>
  <tr>
    <td>Libft &nbsp;authorized</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Write&nbsp; a &nbsp;library &nbsp;that &nbsp;contains &nbsp;ft_printf(), &nbsp;a &nbsp;function &nbsp;that &nbsp;will &nbsp;mimic &nbsp;the &nbsp;original &nbsp;printf()</td>
  </tr>
</table>
<br><br>
You &nbsp;have &nbsp;to &nbsp;recode &nbsp;the &nbsp;printf() &nbsp;function &nbsp;from &nbsp;libc.<br><br>
The &nbsp;prototype&nbsp; of&nbsp; ft_printf() &nbsp;is:<br>
int &nbsp;ft_printf(const &nbsp;char &nbsp;*,&nbsp; ...);<br><br>
Here&nbsp; are&nbsp; the &nbsp;requirements:<br>
<ul>
<li>Don’t &nbsp;implement &nbsp;the &nbsp;buffer &nbsp;management &nbsp;of&nbsp; the &nbsp;original&nbsp; printf().
<li>Your &nbsp;function&nbsp; has&nbsp; to &nbsp;handle &nbsp;the &nbsp;following &nbsp;conversions: &nbsp;<b>cspdiuxX%</b>
<li>Your&nbsp; function &nbsp;will &nbsp;be &nbsp;compared &nbsp;against&nbsp; the&nbsp; original &nbsp;printf().
<li>You &nbsp;must &nbsp;use &nbsp;the &nbsp;command &nbsp;ar &nbsp;to&nbsp; create&nbsp; your&nbsp; library.<br>
Using &nbsp;the &nbsp;libtool&nbsp; command &nbsp;is &nbsp;forbidden.
<li>Your &nbsp;libftprintf.a &nbsp;has &nbsp;to &nbsp;be &nbsp;created &nbsp;at &nbsp;the&nbsp; root&nbsp; of &nbsp;your&nbsp; repository.
</ul>
<br><br>
You &nbsp;have &nbsp;to &nbsp;implement &nbsp;the &nbsp;following &nbsp;conversions:<br>
<ul>
<li>%c &nbsp;Prints&nbsp; a &nbsp;single&nbsp; character.<br>
<li>%s &nbsp;Prints&nbsp; a &nbsp;string &nbsp;(as&nbsp; defined&nbsp; by&nbsp; the&nbsp; common &nbsp;C&nbsp; convention).<br>
<li>%p&nbsp; The &nbsp;void &nbsp;* &nbsp;pointer &nbsp;argument &nbsp;has &nbsp;to &nbsp;be&nbsp; printed&nbsp; in&nbsp; hexadecimal &nbsp;format.<br>
<li>%d &nbsp;Prints&nbsp; a &nbsp;decimal &nbsp;(base &nbsp;10) &nbsp;number.<br>
<li>%i &nbsp;Prints&nbsp; an &nbsp;integer&nbsp; in &nbsp;base &nbsp;10.<br>
<li>%u &nbsp;Prints&nbsp; an&nbsp; unsigned&nbsp; decimal &nbsp;(base &nbsp;10) &nbsp;number.<br>
<li>%x &nbsp;Prints&nbsp; a &nbsp;number&nbsp; in&nbsp; hexadecimal&nbsp; (base 16) &nbsp;lowercase &nbsp;format.<br>
<li>%X&nbsp; Prints&nbsp; a &nbsp;number&nbsp; in&nbsp; hexadecimal&nbsp; (base 16) &nbsp;uppercase &nbsp;format.<br>
<li>%% &nbsp;Prints&nbsp; a&nbsp; percent&nbsp; sign.<br>
</ul>
