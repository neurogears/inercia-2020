---
layout: slides
title: Bonsai @ Inercia 2020
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](./assets/images/bonsai-lettering.svg)

### A visual language for scientific experimentation
<table style="width: 100%;">
  <tr>
    <td width="33%" align="center" valign="bottom">João Frazão</td>
    <td width="33%" align="center"><a href="http://bonsai-rx.org"><strong>bonsai-rx.org</strong></a></td>
    <td width="33%" align="center">Gonçalo Lopes</td>
  </tr>
</table>

<table style="width: 100%;">
  <tr>
    <th width="50%"><img alt="Champalimaud Foundation" src="./assets/images/cf.png" height="100"/></th>
    <th width="50%"><img alt="NeuroGEARS" src="./assets/images/neurogears.svg" align="right"/></th>
  </tr>
</table>

</script>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section data-background="#000000">
    <section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
    <script type="text/template">## Applications</script>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/4q9mFkZ3J_g?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=4q9mFkZ3J_g&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Elena Dreosti, UCL</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/qXqAXgXJPmo?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Lorenza Calcaterra, Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/mJDV07ptQFk?start=40&amp;controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>George Dimitriadis, Kampff Lab</th></tr>
      </table>
    </section>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Devices in systems neuroscience](./assets/images/devices.jpg)

---

![Bonsai workflow editor](./assets/images/editor.jpg)

---

<!-- .element: data-transition="default none" -->
#### A metaphor for observable sequences

<img alt="Nasa twitter account" src="./assets/images/nasatwitter.jpg" width="400"/>

--

<!-- .element: data-transition="none" -->
#### A metaphor for observable sequences

<img alt="Webcam twitter account" src="./assets/images/webcamtwitter.jpg" width="400"/>

---

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/cameracapture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/graycam-marble.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/framepicker-capture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/cameracapture-marble.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/grayscalefile.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/grayscaletransform.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/saveimagesink.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/conditionkey.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

---

<!-- .element: data-transition="default none" -->
##### Operator Categories

![Operator categories](./assets/images/categories-simple.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
##### Operator Categories

![Operator categories](./assets/images/categories.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

---

###### Skip

![Skip](./assets/images/skip.svg)

---

###### Take

![Take](./assets/images/take.svg)

---

###### SkipUntil

![SkipUntil](./assets/images/skipuntil.svg)

---

###### TakeUntil

![TakeUntil](./assets/images/takeuntil.svg)

---

###### CombineLatest

![CombineLatest](./assets/images/combinelatest.svg)

---

<!-- .element: data-transition="default none" -->
###### Transform

![Transform](./assets/images/transform.svg)

--

<!-- .element: data-transition="default none" -->
###### Select

![Select](./assets/images/select.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany

![SelectMany](./assets/images/selectmany.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany: Play audio on cue

![SelectMany](./assets/images/selectmany-playsound-1.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany: Play audio on cue

![SelectMany](./assets/images/selectmany-playsound-2.svg)

---

<!-- .element: data-transition="default none" -->
###### TriggeredWindow

![TriggeredWindow](./assets/images/triggeredwindow.svg)

--

<!-- .element: data-transition="none default" -->
###### TriggeredWindow: Record triggered video

![SelectMany](./assets/images/triggeredwindow-recordclip.svg)


</script>
</section>