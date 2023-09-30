<script>
</script>

<main id="main" class="main">
  <div class="pagetitle">
    <h1>Todo</h1>
    <nav>
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="index.html">Home</a></li>
        <li class="breadcrumb-item">Tables</li>
        <li class="breadcrumb-item active">Data</li>
      </ol>
    </nav>
  </div>
  <!-- End Page Title -->

  <section class="section">
    <div class="row">
      <div class="col-lg-12">
        <div class="card">
          <div class="card-body">
            <div class="head">
              <h5 class="card-title mb-3">Todo</h5>

              <a class="btn btn-info add" href="/admin/add">Add</a>
            </div>

            <!-- Table with stripped rows -->
            <table class="table datatable">
              <thead>
                <tr>
                  <th scope="col">#</th>
                  <th scope="col">Name</th>
                  <th scope="col">Position</th>
                  <th scope="col">Age</th>
                  <th scope="col">Start Date</th>
                  <th scope="col">action</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row">1</th>
                  <td>Brandon Jacob</td>
                  <td>Designer</td>
                  <td>28</td>
                  <td>2016-05-25</td>
                  <td >
                    <a href="/admin/edit">
                        <i class="bi bi-pencil-square" />
                      </a>
                    <a href="/admin/delete" style="width: 50px;">
                      <i class="bi bi-trash" />
                    </a>
                  </td>
                </tr>
                <tr>
                  <th scope="row">2</th>
                  <td>Bridie Kessler</td>
                  <td>Developer</td>
                  <td>35</td>
                  <td>2014-12-05</td>
                  <td >
                    <a href="/admin/edit">
                        <i class="bi bi-pencil-square" />
                      </a>
                    <a href="/admin/delete" style="width: 50px;">
                      <i class="bi bi-trash" />
                    </a>
                  </td>
                </tr>
                
                <tr>
                  <th scope="row">3</th>
                  <td>Ashleigh Langosh</td>
                  <td>Finance</td>
                  <td>45</td>
                  <td>2011-08-12</td>
                  <td >
                    <a href="/admin/edit">
                        <i class="bi bi-pencil-square" />
                      </a>
                    <a href="/admin/delete" style="width: 50px;">
                      <i class="bi bi-trash" />
                    </a>
                  </td>
                </tr>
                <tr>
                  <th scope="row">4</th>
                  <td>Angus Grady</td>
                  <td>HR</td>
                  <td>34</td>
                  <td>2012-06-11</td>
                  <td >
                    <a href="/admin/edit">
                        <i class="bi bi-pencil-square" />
                      </a>
                    <a href="/admin/delete" style="width: 50px;">
                      <i class="bi bi-trash" />
                    </a>
                  </td>
                </tr>
              </tbody>
            </table>
            <!-- End Table with stripped rows -->
          </div>
        </div>
      </div>
    </div>
  </section>
</main>

<!-- End #main -->

<style>
  .head {
    display: flex;
  }

  .add {
    margin: 1em 1em 1em auto;
    padding-left: 2em;
    padding-right: 2em;
    color: white;
  }
</style>
