<script>
    {% assign year = site.data.prevyears | where:"year", site.current_year | first %} 
    location.replace("{{ year.url }}");
</script>