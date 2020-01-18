javascript: (function() {
    const removeElements = (elms) => elms.forEach(el => el.remove());
    removeElements( document.querySelectorAll(".guide16-next-prev"));

    const elements = document.getElementsByClassName("guide16-copyrights c-size");
    while (elements.length > 0) elements[0].remove();

    while (document.getElementsByClassName('social-16')[0]) {
    document.getElementsByClassName('social-16')[0].remove();
    }

    Array.from(document.getElementsByClassName("ob-widget-section ob-first"))
    .forEach(element => element.remove());

    var obrain = document.getElementsByClassName("go15-guide-right");
    if (obrain.length > 0) {
    obrain[0].parentNode.removeChild(obrain[0]);
    }

    if (document.getElementById("disqus_thread")){
    document.getElementById("disqus_thread").style.display = 'none';}

    var adsn = document.getElementsByClassName("ob_what ob-hover");
    if (adsn.length > 0) {
    adsn[0].parentNode.removeChild(adsn[0]);
    }

    var hdrs = document.getElementsByClassName("top-extra-tlo");
    hdrs[0].parentNode.removeChild(hdrs[0]);

    document.getElementById("toc-mobile").remove();
})()
