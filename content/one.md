---js
function permalink(data) {
	return "/one/";
}

const eleventyNavigation = {
	key: One,
	order: 1,
}
---
<p>This is another page.</p>

<hello-component place="world"></hello-component>

<p><a href="index.webc">Go back</a>.</p>
