[![](https://visitor-badge.laobi.icu/badge?page_id=yaso09.ScratchW&left_text=Ziyaretçi+Sayısı)](#)

# Liste-Değişken Çevirici

## Neden Bu Çeviriciye İhtiyacınız Olabilir
Çevrimiçi oyunlar vb. projeler geliştirmek isteyebilirsiniz.
Bu tarz bir proje geliştirmeye kalkıştığınızda eğer verilerinizi listeleri kullanarak sıralarsanız bu listeleri bulut değişkenlerine kaydetmek veya
bu listelerin içeriklerini başka listelere/değişkenlere aktarmak isteyebilirsiniz.
İşte o zaman bu kod blokları işlerinizi kolaylaştıracaktır.

## Nasıl Çalışıyor
Yaptığım kod blokları kolayca listenizdeki elemanları bir değişkene kaydetmeye, sonrasında da değişkenden tekrardan listeye çekmeye yarıyor.

### Değişkenler ve Listeler
<img style="height: 3rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/index.variable.png">
<img style="height: 3rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/letter.variable.png">
<img style="height: 3rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/letter-2.variable.png">
<img style="height: 3rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/split.variable.png">
<img style="height: 3rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/variable.variable.png">

<img style="height: 3rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/list.list.png">

### Bloklar
<img src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/block2.png">

Bu kod bloğundaki
<img style="height: 2rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/ayrac.variables.png">
, listeyi değişkene kaydettiğimizde listenin elemanlarının arasına koyacağımız bir ayraç.
Ben örnek olarak ChatGPT'ye yaptırdığım `\1a2b-3c4d-5e6f-7g8h-9i0j-klmnopqrst\` ayracını kullanıyorum.
Ancak bulut değişkenleri için bu kod bloklarını kullanmak isterseniz sayı kullanmanız gerekecektir.
Bu durumda yine ChatGPT'ye yaptırdığım `4729013586274190837452938105723948102957832104958126301948752639
` ayracını kullanabilirsiniz.
<img style="height: 2rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/variable.variable.png">
, listenin kaydedileceği değişken oluyor.
<img style="height: 2rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/index.variable.png">
ise
<img style="height: 2rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/list.list.png">
in kaçıncı elemanını
<img style="height: 2rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/variable.variable.png">
a kaydedeceğimizi gösteriyor. Gördüğünüz gibi ilk önce 1 numaralı elemanını ekliyoruz. Ardından
<img style="height: 2rem"
src="https://github.com/user-attachments/assets/97ff4310-4fcb-43ce-bbb9-1b61ac455725">
olana kadar
<img style="height: 2rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/index.variable.png">
i 1 arttırıyoruz. Bu sayede
<img style="height: 2rem"
src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/list.list.png">
imiz 


<img src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/block1.png">


<img src="https://raw.githubusercontent.com/yaso09/ScratchW/main/Liste-Degisken-Cevirici/Assets/block3.png">


{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://scratchw.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
