<script lang="ts">
	import { testValue } from '~shared/test';
	import { NoteEntity } from '~entities/notes';
</script>

<h1>Welcome to SvelteKit2</h1>
<p>{testValue}</p>

<hr />

<NoteEntity content="Eat more chips" />
