<script>
  import Card from "../../components/Card.svelte";
</script>

<Card />
<Card>Hello from content</Card>
<Card><h2>Hello from content</h2></Card>
<Card>
  <div slot='card'>CARD COMPO</div>
  <div slot='header'><h3>HEADER COMPO</h3></div>
  <div slot='content'>Content</div>
  <div slot='footer'>FOOTER COMPO</div>
</Card>