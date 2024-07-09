<script lang="ts">
  const currenTime = new Date()
  const currentHour = currenTime.getHours()

  let greeting = "Buenas noches"

  if (currentHour < 12) 
  {
    greeting = "Buenos dias"
  } else if (currentHour < 18) {
    greeting = "Buenas tardes"
  }

</script>

<h2 class="text-4xl font-bold">{greeting}</h2>