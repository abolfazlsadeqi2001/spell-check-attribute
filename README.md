# spell-check-attribute
a text area that allow and doesn't allow spell checking via a checkbox
<script>
	function checkSpelling(element){
		var textAreaElement = document.querySelector("textarea");
		textAreaElement.spellcheck = element.checked;
	}
</script>
