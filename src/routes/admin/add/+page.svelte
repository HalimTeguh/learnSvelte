<script>
</script>

<main id="main" class="main">
  <div class="pagetitle">
    <h1>Form Elements</h1>
    <nav>
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="index.html">Home</a></li>
        <li class="breadcrumb-item">Forms</li>
        <li class="breadcrumb-item active">Elements</li>
      </ol>
    </nav>
  </div>
  <!-- End Page Title -->

  <section class="section">
    <div class="row">
      <div class="col-lg-12">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">General Form Elements</h5>

            <!-- General Form Elements -->
            <form>
              <div class="row mb-3">
                <label for="inputText" class="col-sm-2 col-form-label"
                  >Title</label
                >
                <div class="col-sm-10">
                  <input type="text" class="form-control" />
                </div>
              </div>
              <div class="row mb-3">
                <label for="inputDate" class="col-sm-2 col-form-label"
                  >Deadline Date</label
                >
                <div class="col-sm-10">
                  <input type="date" class="form-control" />
                </div>
              </div>
              <div class="row mb-3">
                <label for="inputTime" class="col-sm-2 col-form-label"
                  >Deadline Time</label
                >
                <div class="col-sm-10">
                  <input type="time" class="form-control" />
                </div>
              </div>

              <div class="row mb-3">
                <!-- svelte-ignore a11y-label-has-associated-control -->
                <label class="col-sm-2 col-form-label">Select</label>
                <div class="col-sm-10">
                  <select class="form-select" aria-label="Mata Kuliah">
                    <option selected>Open this select menu</option>
                    <option value="1">Metodologi Penelitian</option>
                    <option value="2">Data Mining</option>
                    <option value="3">Pemrograman Mobile</option>
                    <option value="4">Tata kelola Teknologi Informasi</option>
                    <option value="5">Perancangan Sumber Daya</option>
                    <option value="6">Kercerdasan Bisnis</option>
                    <option value="7">Sistem Pengambilan Keputusan</option>
                    <option value="8">Bahasa Indonesia</option>
                  </select>
                </div>
              </div>

              <div class="row mb-3">
                <label for="inputPassword" class="col-sm-2 col-form-label">Description</label>
                <div class="col-sm-10">
                  <textarea
                    class="tinymce-editor"
                    style="height: 50px"
                  /><!-- End TinyMCE Editor -->
                </div>
              </div>

              <div class="row mb-3">
                <!-- svelte-ignore a11y-label-has-associated-control -->
                <label class="col-sm-2 col-form-label" />
                <div class="col-sm-10">
                  <button type="submit" class="btn btn-primary"
                    >Submit Form</button
                  >
                  <a class="btn btn-danger" href="/admin">Back</a>
                </div>
              </div>
            </form>
            <!-- End General Form Elements -->
          </div>
        </div>
      </div>
    </div>
  </section>
</main>

<!-- End #main -->

<style>
</style>
