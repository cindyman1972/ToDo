<script>
	import ToDoInput from "../components/ToDoInput.svelte";
	import ToDoList from "../components/ToDoList.svelte";


</script>

<div class="wrapper">
    <div class="ToDo">
     <ToDoInput/>
     <ToDoList/>
</div>

</div>


<style>
.wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;

}
.ToDo {
  max-width: 634px;
  height: 597px;
  background-color: rgba(230, 230, 230, 1);
  display: flex;
  flex-direction: column;
  padding: 44px 62px;
  border-radius: 10px;
  font-size: 20px;

}
</style>