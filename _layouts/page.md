---
layout: default
---
<div class='container-fluid'>
        <div class='row' style='position: relative; height: calc(100vh - 100px); margin-bottom: 100px;'>
            <div class='col-12 col-sm-12 col-md-10 col-lg-10 col-xl-10'>
                <nav class="navbar navbar-dark col-12" style='padding-bottom: 40px; padding-top: 0px;'>
                      <ul class="nav navBox">
                          <li class="nav-item mr-4">
                              <a href="http://ikovylyaev.com" class="nav-link" style='padding-left: 0px!important;'>дизайн</a>
                          </li>
                            <li class="nav-item mr-4">
                              <a href="http://video.ikovylyaev.com" class=" nav-link">фото и видео</a>
                          </li>
                          <li class="nav-item mr-4">
                              <a href="http://nature.ikovylyaev.com" class="nav-link">урал</a>
                          </li>
                             <li class="nav-item">
                              <a href="http://blog.ikovylyaev.com" class="active nav-link">блог</a>
                          </li>
                      </ul>
                  </nav>
		<a href='{{site.url}}' class="badge mt-5 rounded-pill bg-light" style='text-decoration: none; color: #000; font-weight: 200'>на главную</a>
                <h1 style='font-weight: 200!important' class='display-3 mt-2 mb-5'>{{ page.title }}</h1>
                <img src='{{site.url}}/img/logo.svg' class='d-none d-sm-none d-md-inline' style="position: absolute; bottom: 25px; height: 4vh;">
                <div style='position: absolute; bottom: 0px; ' class='d-none d-sm-none d-md-inline'>
                    <a style="color: #fff; text-decoration: none;" href="http://blog.ikovylyaev.com/terms">terms of use</a> | <a style="color: #fff; text-decoration: none;" href="http://blog.ikovylyaev.com/policy">privacy policy</a>
                </div>
            </div>

        </div>
        <div class="post">
		{{ content }}
        </div>
	<img src='{{site.url}}/img/logo.svg' class='d-inline d-sm-inline d-md-none' style="margin-top: 50px; height: 4vh;">
        <div class='d-block d-sm-block d-md-none'>
            <a style="color: #fff; text-decoration: none;" href="http://blog.ikovylyaev.com/terms">terms of use</a> | <a style="color: #fff; text-decoration: none;" href="http://blog.ikovylyaev.com/policy">privacy policy</a>
        </div>
    </div>
	<style>
		.post img{
		object-fit: contain;
		width: 100%;
		height: 70vh;
		background: #333;
		padding: 25px 0;
		margin: 25px 0;
		}
	</style>
