<script>
  import { interval } from "rxjs";
  import { map } from "rxjs/operators";

  let timer = interval(1000).pipe(map(x => x * 2));
</script>

<main>{$timer}</main>
