<template>
<div>
    <h3>Some User Details</h3>
    <p> User Loaded has ID:{{ $route.params.id}}</p>
    <router-link tag="button"
     :to="{name:'editUser' ,
      params: {id: $route.params.id} ,
       query:{name:'adil', email:'adil@gmail.com'}, hash:'#data'}"
        class="btn btn-primary">Edit User</router-link>   
    </div>
</template>