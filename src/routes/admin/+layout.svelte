<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta content="width=device-width, initial-scale=1.0" name="viewport" />

    <title>Tables / Data - NiceAdmin Bootstrap Template</title>
    <meta content="" name="description" />
    <meta content="" name="keywords" />

    <!-- Favicons -->
    <link href="/src/lib/img/favicon.png" rel="icon" />
    <link href="/src/lib/img/apple-touch-icon.png" rel="apple-touch-icon" />

    <!-- Google Fonts -->
    <link href="https://fonts.gstatic.com" rel="preconnect" />
    <link
      href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Nunito:300,300i,400,400i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i"
      rel="stylesheet"
    />

    <!-- Vendor CSS Files -->
    <link
      href="/src/lib/vendor/bootstrap/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <link
      href="/src/lib/vendor/bootstrap-icons/bootstrap-icons.css"
      rel="stylesheet"
    />
    <link
      href="/src/lib/vendor/boxicons/css/boxicons.min.css"
      rel="stylesheet"
    />
    <link href="/src/lib/vendor/quill/quill.snow.css" rel="stylesheet" />
    <link href="/src/lib/vendor/quill/quill.bubble.css" rel="stylesheet" />
    <link href="/src/lib/vendor/remixicon/remixicon.css" rel="stylesheet" />
    <link href="/src/lib/vendor/simple-datatables/style.css" rel="stylesheet" />

    <!-- Template Main CSS File -->
    <link href="/src/lib/css/style.css" rel="stylesheet" />

    <!-- =======================================================
  * Template Name: NiceAdmin
  * Updated: Sep 18 2023 with Bootstrap v5.3.2
  * Template URL: https://bootstrapmade.com/nice-admin-bootstrap-admin-html-template/
  * Author: BootstrapMade.com
  * License: https://bootstrapmade.com/license/
  ======================================================== -->
  </head>

  <body>
    <!-- ======= Header ======= -->
    <header id="header" class="header fixed-top d-flex align-items-center">
      <div class="d-flex align-items-center justify-content-between">
        <a href="/admin" class="logo d-flex align-items-center">
          <img src="/src/lib/img/logo.png" alt="" />
          <span class="d-none d-lg-block">NiceAdmin</span>
        </a>
        <i class="bi bi-list toggle-sidebar-btn" />
      </div>
      <!-- End Logo -->

      <nav class="header-nav ms-auto">
        <ul class="d-flex align-items-center">
          <li class="nav-item dropdown pe-3">
            <a
              class="nav-link nav-profile d-flex align-items-center pe-0"
              href="/"
              data-bs-toggle="dropdown"
            >
              <img
                src="/src/lib/img/profile-img.jpg"
                alt="Profile"
                class="rounded-circle"
              />
              <span class="d-none d-md-block dropdown-toggle ps-2"
                >K. Anderson</span
              >
            </a><!-- End Profile Iamge Icon -->

            <ul
              class="dropdown-menu dropdown-menu-end dropdown-menu-arrow profile"
            >
              <li class="dropdown-header">
                <h6>Kevin Anderson</h6>
              </li>
              <li>
                <hr class="dropdown-divider" />
              </li>

              <li>
                <a
                  class="dropdown-item d-flex align-items-center"
                  href="/logout"
                >
                  <i class="bi bi-box-arrow-right" />
                  <span>Sign Out</span>
                </a>
              </li>
            </ul>
            <!-- End Profile Dropdown Items -->
          </li>
          <!-- End Profile Nav -->
        </ul>
      </nav>
      <!-- End Icons Navigation -->
    </header>
    <!-- End Header -->

    <!-- ======= Sidebar ======= -->
    <aside id="sidebar" class="sidebar">
      <ul class="sidebar-nav" id="sidebar-nav">
        <li class="nav-item">
          <a class="nav-link collapsed" href="index.html">
            <i class="bi bi-grid" />
            <span>Dashboard</span>
          </a>
        </li>
        <!-- End Dashboard Nav -->

        <li class="nav-item">
          <a
            class="nav-link"
            data-bs-target="#tables-nav"
            data-bs-toggle="collapse"
            href="/admin"
          >
            <i class="bi bi-layout-text-window-reverse" /><span>Tables</span><i
              class="bi bi-chevron-down ms-auto"
            />
          </a>
          <ul
            id="tables-nav"
            class="nav-content collapse show"
            data-bs-parent="#sidebar-nav"
          >
            <li>
              <a href="tables-data.html" class="active">
                <i class="bi bi-circle" /><span>Data Tables</span>
              </a>
            </li>
          </ul>
        </li>
        <!-- End Tables Nav -->
      </ul>
    </aside>
    <!-- End Sidebar-->

    <slot />

    <!-- ======= Footer ======= -->
    <footer id="footer" class="footer">
      <div class="copyright">
        &copy; Copyright <strong><span>NiceAdmin</span></strong>. All Rights
        Reserved
      </div>
      <div class="credits">
        <!-- All the links in the footer should remain intact. -->
        <!-- You can delete the links only if you purchased the pro version. -->
        <!-- Licensing information: https://bootstrapmade.com/license/ -->
        <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/nice-admin-bootstrap-admin-html-template/ -->
        Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a>
      </div>
    </footer>
    <!-- End Footer -->

    <a
      href="/admin"
      class="back-to-top d-flex align-items-center justify-content-center"
      ><i class="bi bi-arrow-up-short" /></a
    >

    <!-- Vendor JS Files -->
    <!-- Vendor JS Files -->
    <script src="/src/lib/vendor/apexcharts/apexcharts.min.js"></script>
    <script src="/src/lib/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
    <script src="/src/lib/vendor/chart.js/chart.umd.js"></script>
    <script src="/src/lib/vendor/echarts/echarts.min.js"></script>
    <script src="/src/lib/vendor/quill/quill.min.js"></script>
    <script
      src="/src/lib/vendor/simple-datatables/simple-datatables.js"
    ></script>
    <script src="/src/lib/vendor/tinymce/tinymce.min.js"></script>
    <script src="/src/lib/vendor/php-email-form/validate.js"></script>

    <!-- Template Main JS File -->
    <!-- Template Main JS File -->
    <script src="/src/lib/js/main.js"></script>
  </body>
</html>

<style>
  body {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI",
      Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif,
      "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
      "Noto Color Emoji";
  }
</style>
