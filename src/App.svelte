<script>
  import Todos from "./components/todos.svelte";

  let todos = [
    { id: 1, name: "Create a Svelte start app", completed: true },
    { id: 2, name: "Create your first component", completed: true },
    { id: 3, name: "Complete the rest of the tutorial", completed: false },
  ];
</script>

<Todos {todos} />
