<template>
  <main>
    <h1>Task Board</h1>
    <p>Create a list of tasks</p>

    <div class="create-new">
      <input type="text" v-model="newTask" placeholder="Add new task" @keypress.enter="addTask">
      <button @click="addTask">Add</button>
    </div>
  </main>
</template>
