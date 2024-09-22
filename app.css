var num = document.querySelector("#input")
var div = document.querySelector("ol")
var array = []




function render(){
    div.innerHTML = ""
    for(i=0;  i < array.length; i++){
        div.innerHTML += `<li>${array[i]}
        <button  onclick="deletTodo(${i})">delete</button>
        <button onclick="editTodo(${i})">Edit</button>
        </li>`
}}
function sub(){
    array.push(num.value) 
render();
    num.value = ""
}


function deletTodo(index){
    div.innerHTML = ""
    array.splice(index, 1)
    // render()
}
function editTodo(index){
    // div.innerHTML = ""
    var edit = prompt()
     array.splice(index, 1, edit)
render()
}



