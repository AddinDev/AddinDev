[![HitCount](http://hits.dwyl.com/AddinDev/AddinDev.svg)](http://hits.dwyl.com/AddinDev/AddinDev)
<webview id="foo" src="https://www.github.com/" style="display:inline-flex; width:640px; height:480px"></webview>
<script>
  onload = () => {
    const webview = document.querySelector('webview')
    const indicator = document.querySelector('.indicator')

    const loadstart = () => {
      indicator.innerText = 'loading...'
    }

    const loadstop = () => {
      indicator.innerText = ''
    }

    webview.addEventListener('did-start-loading', loadstart)
    webview.addEventListener('did-stop-loading', loadstop)
  }
</script>



### Ohayo!, I'm Addin 👋

- 🔭 I’m a intermediate iOS Developer
- 🌱 Learn from the internet
- 🏠 Jakarta Pusat
- 📬 How to reach me : <a href="mailto:addinsatria2004@gmail.com">Contact me!</a>

### About Me

<p align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AddinDev&theme=radical&hide_langs_below=1&layout=compact">
  <img src="https://media.giphy.com/media/DxgYCBC9lOHQrZC6ab/giphy.gif" width="200" height="200" />
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=AddinDev&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=151515">
</p> 

