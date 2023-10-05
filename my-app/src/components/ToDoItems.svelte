    <script>

    </script>
    
    <div class="ToDo__list__item ToDo__list__item-done">
        <input type="checkbox" class="ToDo__list__item-check">
        <p class="text">Task</p>
        <button class="ToDo__list__item-btn"></button>
    </div>

    <style>
        .ToDo__list__item {
  display: grid;
  grid-template-columns: auto 1fr 10%;
  align-items: center;
  height: 65px;
  margin: 20px;
  background-color: rgba(255, 235, 235, 1);
  border: none;
  border-radius: 10px;

}

.ToDo__list__item-done {
  background-color: green;
}

.ToDo__list__item-check {
  margin-left: 20px;
}

.text {
  background: none;
  border: none;
  margin-left: 20px;
}

.ToDo__list__item-btn {
  background: none;
  border: none;
  width: 50px;
  height: 50px;
  background: url(/my-app/static/trash.svg) no-repeat center;
}
    </style>