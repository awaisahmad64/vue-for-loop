<template>
<div>
    <h1>This is for loop component.</h1>
    <table border="1px" style="border-collapse: collapse;">
      <tr>
          <td>ID</td>
          <td>Name</td>
          <td>Eamil</td>
      </tr>
      <tr v-for="user in users" :key="user.id">
          <td>{{user.id}}</td>
          <td>{{user.name}}</td>
          <td>{{user.name}}</td>
      </tr>

    </table>
</div>
</template>
<script>
export default {
    name:'ForLoop',data(){
        return { users:[
            {id:1,name:'Awais Sandhu',eamil:'awais@gmail.com'},
            {id:2,name:'Abbas Sandhu',eamil:'abbas@gmail.com'},
            {id:3,name:'Tayyab Sandhu',eamil:'tayyab@gmail.com'},
            {id:4,name:'Uzair Sandhu',eamil:'uzari@gmail.com'}
            
        ]
    }
    }
}
</script>
