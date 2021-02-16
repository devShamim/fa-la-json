# FontAwesome 5 and LineAwesome json
Generate json file from FontAwesome

## FontAwesome

<pre>
    var faRegular = [];
    document.querySelectorAll('.select-all').forEach((elm, id)=>{
      faRegular.push(elm.innerText);
    })
    JSON.stringify(faRegular)
</pre>

## LineAwesome

<pre>
  var laBrands = [];
  document.querySelectorAll('#BrandIcons .name').forEach((elm, id)=>{
    laBrands.push(elm.innerText);
  })
  JSON.stringify(laBrands)
</pre>
