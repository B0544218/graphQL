mutation{
  createTodo(input:{
    text:"Hi"
    userId:"1"
    userName:"abc"
  })
  {
    id
    text
    done
    user
  }
}


query{
  todos{
    id
    text
    done
    user
  }
}
