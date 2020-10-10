---
layout: search
title: Busca
permalink: /search/
---

{{ Teste de busca }}

Digite a sua busca e aparece automaticamente

<form onsubmit="return false;">
  <input type="input" id="search" class="search-input" placeholder="{{ site.data.text[site.locale].search_placeholder_text | default: 'Enter your search term...' }}" autofocus>
</form>

<div id="results"></div>
