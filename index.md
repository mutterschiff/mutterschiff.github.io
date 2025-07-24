---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<p/>
<br/>

## Wie man einen Weidling umbaut und die Aare runterfährt. 

> ### Eine Anleitung in {{ site.posts | size }} Schritten.

<div>
	<img src="/img2/20220806__ms_res_aaremeer_32.jpg">
</div>
<div>
	<b>D'Aare geit ids Meer. U im Tierpark hets Meersäuli.</b> <i>Stiller Has - Aare</i>
</div>


<script>
	// Changing the "Read more..." excerpts infos as it doesn't seem to be easy doable otherwise
	document.addEventListener('DOMContentLoaded', function () {
		document.querySelectorAll('a.read-more').forEach(el => {
			el.textContent = ' … weiter lesen';
		});
	});
</script>
