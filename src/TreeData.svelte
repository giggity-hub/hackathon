<script>
    export let family;
    export let address;
    export let heading;
    export let waterCycle = "15L per week";
    export let health = "ok";

</script>


<div class="card" style="width: 18rem;">
    <img class="card-img-top" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/2015-10-21_13_20_10_Sugar_Maple_during_autumn_along_Patton_Drive_in_Ewing%2C_New_Jersey.jpg/300px-2015-10-21_13_20_10_Sugar_Maple_during_autumn_along_Patton_Drive_in_Ewing%2C_New_Jersey.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">{heading}</h5>
      <ul class="list-group">
        <li class="list-group-item">Adresse: {address}</li>
        <li class="list-group-item">Familie: {family}</li>
        <li class="list-group-item">Water cycle: {waterCycle} </li>
        <li class="list-group-item">Health: {health}</li> 
      <br/>
        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModalLong">
            Launch demo modal
        </button>
      </ul>
    </div>
  </div>



  