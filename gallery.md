---
layout: page
title: Gallery
---

<div class="gallery-page">

<p>
Photographs from the lab over the years, including gatherings, conferences, workshops, and other memorable moments.
</p>

<style>

.gallery-page .gallery-section {
    margin: 2.5rem 0;
}

.gallery-page .gallery-section h3 {
    margin-bottom: 1.2rem;
    text-align: center;
}

.gallery-page .gallery {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1.75rem;
    justify-items: center;
}

.gallery-page .gallery figure {
    margin: 0;
    overflow: hidden;
    border-radius: 6px;
    transition: transform .25s ease;
}

.gallery-page .gallery a {
    display: block;
    cursor: zoom-in;
    text-decoration: none;
}

.gallery-page .gallery figure img {
    width: 100%;
    max-width: 650px;
    height: auto;
    display: block;
    border: 1px solid #ddd;
    border-radius: 6px;
    background: white;

    transition:
        transform .25s ease,
        box-shadow .25s ease,
        border-color .25s ease;
}

.gallery-page .gallery figure:hover {
    transform: translateY(-4px);
}

.gallery-page .gallery figure:hover img {
    transform: scale(1.03);
    box-shadow: 0 8px 20px rgba(0,0,0,.18);
    border-color: #bbb;
}

.gallery-page .gallery figcaption {
    margin-top: .6rem;
    text-align: center;
    font-size: .9em;
    color: #666;
    transition: color .25s ease;
}

.gallery-page .gallery figure:hover figcaption {
    color: #222;
}

.gallery-page .gallery a:focus img {
    outline: none;
    box-shadow: 0 0 0 3px rgba(0,120,255,.35);
}

/* ===========================
   LIGHTBOX
   =========================== */

#lightbox {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,.9);

    display: flex;
    justify-content: center;
    align-items: center;

    opacity: 0;
    visibility: hidden;

    transition: opacity .25s ease;
    z-index: 9999;
}

#lightbox.show {
    opacity: 1;
    visibility: visible;
}

#lightbox img {
    max-width: 92vw;
    max-height: 92vh;

    border-radius: 6px;
    box-shadow: 0 15px 40px rgba(0,0,0,.45);

    cursor: zoom-out;

    animation: zoomIn .25s ease;
}

#lightbox-close {
    position: absolute;
    top: 20px;
    right: 30px;

    font-size: 40px;
    color: white;

    cursor: pointer;
    user-select: none;
}

@keyframes zoomIn {

    from {
        transform: scale(.92);
        opacity: 0;
    }

    to {
        transform: scale(1);
        opacity: 1;
    }

}

</style>

<!-- ===================== -->
<!-- LAB GROUP SECTION -->
<!-- ===================== -->

<div class="gallery-section">

<h3>Group Photos &amp; Social Events</h3>

<div class="gallery">


<figure>
<a href="/assets/gallery/2026-lab-group.jpg">
<img src="/assets/gallery/2026-lab-group.jpg" alt="Lab Members 2026">
</a>
<figcaption>Lab Members &bull; July 2026</figcaption>
</figure>


<figure>
<a href="/assets/gallery/2022-lab-group.png">
<img src="/assets/gallery/2022-lab-group.png" alt="Lab Members 2022">
</a>
<figcaption>Lab Members &bull; May 2022</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2019-lab-group-fall.jpg">
<img src="/assets/gallery/2019-lab-group-fall.jpg" alt="Lab Members 2019">
</a>
<figcaption>Lab Members &bull; October 2019</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2019-lab-group.jpg">
<img src="/assets/gallery/2019-lab-group.jpg" alt="Lab Members 2019">
</a>
<figcaption>Lab Members &bull; February 2019</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2022-lab-social1.jpg">
<img src="/assets/gallery/2022-lab-social1.jpg" alt="Lab Social">
</a>
<figcaption>Social &bull; January 2022</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2022-lab-social2.jpg">
<img src="/assets/gallery/2022-lab-social2.jpg" alt="Lab Social">
</a>
<figcaption>Social &bull; September 2022</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2019-lab-visit.jpg">
<img src="/assets/gallery/2019-lab-visit.jpg" alt="Lab Visit">
</a>
<figcaption>Lab Visit &bull; March 2019</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2018-lab-hike.jpg">
<img src="/assets/gallery/2018-lab-hike.jpg" alt="Lab Hike">
</a>
<figcaption>Eagle Bluffs Hike (BC) &bull; July 2018</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2017-lab-social.jpg">
<img src="/assets/gallery/2017-lab-social.jpg" alt="Lab Social">
</a>
<figcaption>Social &bull; May 2017</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2015-lab-social.jpg">
<img src="/assets/gallery/2015-lab-social.jpg" alt="Lab Social">
</a>
<figcaption>Social &bull; June 2015</figcaption>
</figure>

</div>
</div>

<!-- ===================== -->
<!-- CONFERENCES SECTION -->
<!-- ===================== -->

<div class="gallery-section">

<h3>Conferences &amp; Workshops</h3>

<div class="gallery">

<figure>
<a href="/assets/gallery/2023-recomb-istanbul.jpg">
<img src="/assets/gallery/2023-recomb-istanbul.jpg" alt="RECOMB 2023">
</a>
<figcaption>RECOMB &bull; Istanbul, Türkiye (2023)</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2023-recombseq-istanbul.jpg">
<img src="/assets/gallery/2023-recombseq-istanbul.jpg" alt="RECOMB-Seq 2023">
</a>
<figcaption>RECOMB-Seq &bull; Istanbul, Türkiye (2023)</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2018-recomb-france.jpg">
<img src="/assets/gallery/2018-recomb-france.jpg" alt="RECOMB 2018">
</a>
<figcaption>RECOMB &bull; Paris, France (2018)</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2018-recomb-france-social1.jpg">
<img src="/assets/gallery/2018-recomb-france-social1.jpg" alt="RECOMB Social">
</a>
<figcaption>RECOMB Social &bull; Paris, France (2018)</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2018-recomb-france-social2.jpg">
<img src="/assets/gallery/2018-recomb-france-social2.jpg" alt="RECOMB Social">
</a>
<figcaption>RECOMB Social &bull; Paris, France (2018)</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2017-recombseq-hongkong.jpg">
<img src="/assets/gallery/2017-recombseq-hongkong.jpg" alt="RECOMB-Seq 2017">
</a>
<figcaption>RECOMB-Seq &bull; Hong Kong (2017)</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2015-ISMB-dublin.jpg">
<img src="/assets/gallery/2015-ISMB-dublin.jpg" alt="ISMB 2015">
</a>
<figcaption>ISMB &bull; Dublin, Ireland (2015)</figcaption>
</figure>

<figure>
<a href="/assets/gallery/2015-ISMBhitseq-dublin.jpg">
<img src="/assets/gallery/2015-ISMBhitseq-dublin.jpg" alt="HiTSeq Workshop">
</a>
<figcaption>HiTSeq Workshop &bull; ISMB 2015, Dublin</figcaption>
</figure>

</div>
</div>

</div>

<!-- ===========================
     LIGHTBOX OVERLAY
     =========================== -->

<div id="lightbox">

    <span id="lightbox-close">&times;</span>

    <img id="lightbox-image" src="" alt="Expanded image">

</div>

<script>

document.addEventListener("DOMContentLoaded", function () {

    const lightbox = document.getElementById("lightbox");
    const lightboxImg = document.getElementById("lightbox-image");
    const closeBtn = document.getElementById("lightbox-close");

    // Attach to every gallery image automatically
    document.querySelectorAll(".gallery-page a").forEach(function(link) {

        const href = link.getAttribute("href") || "";

        if (!href.match(/\.(png|jpg|jpeg|gif|webp)$/i))
            return;

        link.addEventListener("click", function(e) {

            e.preventDefault();

            lightboxImg.src = href;
            lightbox.classList.add("show");
            document.body.style.overflow = "hidden";

        });

    });

    function closeLightbox() {

        lightbox.classList.remove("show");

        document.body.style.overflow = "";

        // remove image after fade-out
        setTimeout(function() {
            lightboxImg.src = "";
        }, 250);

    }

    closeBtn.addEventListener("click", closeLightbox);

    lightbox.addEventListener("click", function(e) {

        if (e.target === lightbox) {
            closeLightbox();
        }

    });

    document.addEventListener("keydown", function(e) {

        if (e.key === "Escape") {
            closeLightbox();
        }

    });

});

</script>
