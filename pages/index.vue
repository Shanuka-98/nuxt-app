<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-md-12 ">
          <div class="card">
            <div class="card-header text-center">
              <h3>Student Details</h3>
            </div>
            <div class="card-body">
              <div class="row">
                <div class="col-md-11 mb-4">
                  <table class="table mt-4 align-middle text-center table-hover">
                    <thead>
                      <tr>
                        <th scope="col">#</th>
                        <th scope="col">Id</th>
                        <th scope="col">Name</th>
                        <th scope="col">Age</th>
                        <th scope="col">Status</th>
                        <th scope="col">Image</th>
                        <th scope="col">Action</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row"></th>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td>
                          <button class="btn btn-primary btn-xs">Edit</button>
                          <button class="btn btn-danger btn-xs">Delete</button>
                          <button class="btn btn-success btn-xs">Active</button>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  layout: 'dashboard',
}

</script>


<style>


</style>
