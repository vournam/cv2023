<!DOCTYPE html>
<!--[if IE 10]><html lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml" class="ie10"><![endif]-->
<!--[if !IE]><!--><html lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml" class="noie"><!--<![endif]-->
<head>
  <!--/ FOUC workaround
  ========================================================================= /-->
  <style>
    html {visibility: hidden; opacity: 0; display: none;}
  </style>

  <!--/  Basic Page Needs
  ========================================================================= /-->
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1" />
  <meta http-equiv="Content-Type"    content="text/html; charset=utf-8" />

  <title>{{person.name.full}} - CV, Resume and Portfolio :: Homepage</title>

  <!--/  Mobile Specific Metas
  ========================================================================= /-->
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=3.0, user-scalable=yes" />

  <!--/  Metas
  ========================================================================= /-->
  <meta name="author"        content="{{author.name.full}}" />
  <meta name="description"   content="Personal resume of {{person.name.full}}" />
  <meta name="generator"     content="{{engine.name}} v{{engine.version}}" />
  <meta name="keywords"      content="cv, resume, template, portfolio, portfolio-website, IT, resume-website, cv-website, web-cv, c++v" />
  <meta name="language"      content="en" />
  <meta name="revisit-after" content="15 days" />
  <meta name="robots"        content="index, nofollow, archive" />
  <meta name="title"         content="{{person.name.full}} - CV, Resume and Portfolio" />
  <meta name="theme-color"   content="#000000" />

  <link rel="canonical" href="http://cv.gsm-center.com.ua/" />
  <link rel="manifest"  href="/manifest.json" />

  <!--/  Metas for Crawlers
  ========================================================================= /-->
  <meta property="og:locale"       content="en_US" />
  <meta property="og:type"         content="website" />
  <meta property="og:title"        content="{{person.name.full}} - Modern CV, Resume and Portfolio" />
  <meta property="og:description"  content="CV of {{person.name.full}}" />
  <meta property="og:image"        content="assets/img/Avatar-rhomb-md.webp" />
  <meta property="og:image:type"   content="image/webp" />
  <meta property="og:image:alt"    content="Photo of {{person.name.full}}" />
  <meta property="og:image:height" content="358" />
  <meta property="og:image:width"  content="358" />
  <meta property="og:site_name"    content="CV, Resume and Portfolio - {{person.name.full}}" />
  <meta property="og:url"          content="http://cv.gsm-center.com.ua/" />
  <meta property="og:updated_time" content="{{built.full}}" />
  <meta property="og:see_also"     content="{{author.url}}" />

  <!--/  Fonts
  ========================================================================= /-->
  <!--/  Google Web Fonts  /-->
  <!-- <link type="text/css" rel="stylesheet" media="screen" href="http://fonts.googleapis.com/css?family=Roboto:300,400,500,700" id="css-font-roboto" /> -->
  <!-- <link type="text/css" rel="stylesheet" media="screen" href="http://fonts.googleapis.com/css?family=Lato:300,400,700" id="css-font-lato" /> -->

  <!--/  Preload
  ========================================================================= /-->
  <link rel="preload" crossOrigin="anonymous" as="font" type="font/woff2" href="assets/webfonts/fa-regular-400.woff2" />
  <link rel="preload" crossOrigin="anonymous" as="font" type="font/woff2" href="assets/webfonts/fa-brands-400.woff2" />
  <link rel="preload" crossOrigin="anonymous" as="font" type="font/woff2" href="assets/webfonts/fa-solid-900.woff2" />
  <!-- <link rel="preload" crossOrigin="anonymous" as="font" type="font/woff2" href="https://fonts.gstatic.com/s/roboto/v27/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2&display=swap" /> -->
  <!-- <link rel="preload" crossOrigin="anonymous" as="font" type="font/woff2" href="https://fonts.gstatic.com/s/roboto/v27/KFOlCnqEu92Fr1MmSU5fBBc4AMP6lQ.woff2&display=swap" /> -->
  <link rel="preload" as="image" type="image/webp" href="assets/img/home2.webp" />

  <!--/  Styles
  ========================================================================= /-->
  <!--/  Bower Bundle  /-->
  <link rel="preload" crossOrigin="anonymous" as="style" href="assets/css/bower-bundle.css" onload="this.onload=null;this.rel='stylesheet'" id="css-bower-bundle" />
  <noscript><link rel="stylesheet" href="assets/css/bower-bundle.css" id="css-bower-bundle-noscript" /></noscript>

  <!--/  Frontend Bundle  /-->
  <link rel="preload" crossOrigin="anonymous" as="style" href="assets/css/frontend-bundle.css" onload="this.onload=null;this.rel='stylesheet'" id="css-frontend-bundle" />
  <noscript><link rel="stylesheet" href="assets/css/frontend-bundle.css" id="css-frontend-bundle-noscript" /></noscript>

  <!--/  Theme  /-->
  <!-- <link type="text/css" rel="stylesheet" media="screen" href="assets/css/theme.css" id="css-theme" /> -->

  <!--/ HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries /-->
  <!--[if lt IE 9]> <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script> <![endif]-->
  <!--[if lt IE 9]> <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script> <![endif]-->

  <!--/  Mobile
  ========================================================================= /-->
  <link rel="apple-touch-icon-precomposed" sizes="144x144" href="assets/img/ico/apple-touch-icon-144-precomposed.webp" />
  <link rel="apple-touch-icon-precomposed" sizes="114x114" href="assets/img/ico/apple-touch-icon-114-precomposed.webp" />
  <link rel="apple-touch-icon-precomposed" sizes="72x72"   href="assets/img/ico/apple-touch-icon-72-precomposed.webp" />
  <link rel="apple-touch-icon-precomposed" sizes=""        href="assets/img/ico/apple-touch-icon-57-precomposed.webp" />

  <!--/  Favicon
  ========================================================================= /-->
  <link type="image/x-icon" href="favicon.webp" rel="icon" />
  <link type="image/x-icon" href="favicon.webp" rel="shortcut icon" />

</head>

<body data-spy="scroll" data-target="#navbar-custom" data-env="{{app.env}}">

  <!--/  Preloader  /-->
  <div id="tt-preloader">
    <div id="pre-status">
      <div class="preload-placeholder"></div>
    </div>
  </div>

  <div class="release" id="release"><small>v{{version}}-b{{cntr}}</small></div>

  <!--/  Home  /-->
  <section id="home" class="tt-fullHeight" data-stellar-vertical-offset="50" data-stellar-background-ratio="0.5">
    <div class="intro">
      <div class="intro-sub wow" data-wow-duration="3.0s" data-wow-delay="0.0s">{{person.name.full}}</div>
      <h1 class="wow" data-wow-duration="2.7s" data-wow-delay="0.3s">
        <span class="first">{{person.home.pos-prefix}}</span> <span class="">{{person.home.pos-title}}</span>
      </h1>
      <p class="wow" data-wow-duration="2.5s" data-wow-delay="0.5s">{{person.home.pos-tags}}</p>

      <div id="social-icons" class="social-icons">
        <ul class="list-inline">
          <li class="wow" data-wow-duration="1.4s" data-wow-delay="1.618s">
            <a target="_blank" rel="noopener" href="{{person.socials.linkedin.url}}"><i class="{{person.socials.linkedin.icon}}" title="{{person.socials.linkedin.title}}"></i></a>
          </li>
          <li class="wow" data-wow-duration="1.618s" data-wow-delay="1.4s">
            <a target="_blank" rel="noopener" href="{{person.socials.github.url}}"><i class="{{person.socials.github.icon}}" title="{{person.socials.github.title}}"></i></a>
          </li>
          <li class="wow" data-wow-duration="1.8s" data-wow-delay="1.2s">
            <a target="_blank" rel="noopener" href="{{person.socials.bitbucket.url}}"><i class="{{person.socials.bitbucket.icon}}" title="{{person.socials.bitbucket.title}}"></i></a>
          </li>
          <li class="wow" data-wow-duration="2.0s" data-wow-delay="1.0s">
            <a target="_blank" rel="noopener" href="{{person.socials.dockerhub.url}}"><i class="{{person.socials.dockerhub.icon}}" title="{{person.socials.dockerhub.title}}"></i></a>
          </li>
        </ul>
      </div> <!--/ /.social-icons /-->
    </div>

    <div class="mouse-icon">
      <div class="wheel"></div>
    </div>
  </section><!--/ End Home Section /-->

  <!--/  Navigation  /-->
  <header class="header" id="navbar-custom">
    <nav class="navbar navbar-custom" role="navigation">
      <div class="container">

        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#custom-collapse">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand hidden" href="index.html">
            <!-- <img class="hidden" src="assets/img/logo.png" max-width="200px" max-height="46px" width="200px" height="46px" alt="{{author.nick}}" /> -->
          </a>
        </div>

        <div class="collapse navbar-collapse" id="custom-collapse">
          <ul class="nav navbar-nav navbar-right" role="tablist">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#resume">Resume</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contacts</a></li>
          </ul>
        </div>

      </div><!--/ .container /-->
    </nav>
  </header><!--/ End Navigation /-->

  <!--/  About  /-->
  <section id="about" class="about-section section-padding">
    <div class="container">
      <h2 class="section-title wow" data-wow-duration="1.5s">Bio</h2>

      <div class="row">

        <div class="col-md-4 col-md-push-8">
          <div class="biography">
            <div class="myphoto wow" id="avatar" data-wow-duration="1.0s">
              <picture>
                <!-- <source srcset="assets/img/Avatar-rhomb-md.png" type="image/png" > -->
                <img src="assets/img/Avatar-rhomb-md.webp" class="media-object" width="358px" height="358px" alt="{{person.name.full}}" />
              </picture>
            </div>
            <ul class="list-check">
              <li class="row">
                <div class="col-xs-2 col-sm-6 col-md-2 col-lg-6">
                  <i class="fa fa-fw fa-id-badge"></i>
                  <strong class="hidden-xs hidden-md">Name:</strong>
                </div>
                <div class="col-xs-10 col-sm-6 col-md-10 col-lg-6"><span>{{person.name.full}}</span></div>
              </li>
              <li class="row">
                <div class="col-xs-2 col-sm-6 col-md-2 col-lg-6">
                  <i class="fa fa-fw fa-calendar"></i>
                  <strong class="hidden-xs hidden-md">Birth:</strong>
                </div>
                <div class="col-xs-10 col-sm-6 col-md-10 col-lg-6">{{person.bio.birth}}</div>
              </li>
              <li class="row">
                <div class="col-xs-2 col-sm-6 col-md-2 col-lg-6">
                  <i class="fa fa-fw fa-home"></i>
                  <strong class="hidden-xs hidden-md">Location:</strong>
                </div>
                <div class="col-xs-10 col-sm-6 col-md-10 col-lg-6">{{person.bio.location.full}}</div>
              </li>
              <li class="row">
                <div class="col-xs-2 col-sm-6 col-md-2 col-lg-6">
                  <i class="fa fa-fw fa-globe"></i>
                  <strong class="hidden-xs hidden-md">Citizenship:</strong>
                </div>
                <div class="col-xs-10 col-sm-6 col-md-10 col-lg-6">{{person.bio.citizenship}}</div>
              </li>
            </ul>
          </div>
        </div> <!--/ col-md-4 /-->

        <div class="col-md-8 col-md-pull-4">

          <div class="short-info" id="objective">
            <h3 class="wow">Objective</h3>
            <p class="wow">
              Mathematician and MSc student in Human-Computer Interaction (HCI)
            </p>
          </div>

          <div class="short-info" id="scopes">
            <h3 class="wow">Scopes</h3>
            <ul class="row list-check">
              <li class="col-xs-12 col-md-6 wow" id="scope-04"><i class="fas fa-fw fa-check"></i>Frontend&nbsp;Development</li>
              <li class="col-xs-12 col-md-6 wow" id="scope-05"><i class="fas fa-fw fa-check"></i>User Experience&nbsp;Research</li>
              <li class="col-xs-12 col-md-6 wow" id="scope-06"><i class="fas fa-fw fa-check"></i>UI/UX&nbsp;Design</li>
            </ul>
          </div>

          <div class="short-info" id="selfie">
            <h3 class="wow">Selfie</h3>
            <p class="wow">I'm a Mathematician and a Master's student in Human-Computer Interaction (HCI). During my master's degree I have worked on projects related to Front-End Development and UI/UX Design. I have experience in HTML5, CSS3, Node.js, Express framework and React.js. I have also worked on 3 projects for creating mockups with Balsamiq and Figma tools. Additionally, I have experience in creating user personas, user scenarios as well as familiarity with storyboards.
            </p>
          </div>
  <!--/ Resume /-->
  <section id="resume" class="resume-section section-padding">
    <div class="container">
      <h2 class="section-title wow" data-wow-duration="1.5s">Resume</h2>

      <div class="row resume-education">
        <div class="col-md-12">

          <div id="edu" class="resume-title wow">
            <h2 class="text-center text-primary">Education</h2>
          </div>

          <div class="resume">
            <ul class="timeline">

              <li class="">
                <div class="posted-date">
                  <span class="month">October 2021 - now</span>
                </div><!--/ /posted-date /-->

                <div id="edu-01" class="panel panel-success timeline-panel wow" data-wow-duration="1.0s">
                  <div class="timeline-content">

                    <div class="panel-heading timeline-heading row">
                      <div class="col-md-10 col-xs-9 pull-left">
                        <h3 class="panel-title">Master's degree</h3>
                        <p class="text-danger"> - Grade: 8.45, having completed all courses except for the master thesis, which is in progress.</p>
                      </div>

                      <div class="col-md-2 col-xs-3 pull-right text-center">
                        <i class="fas fa-3x fa-user-graduate text-success"></i>
                      </div>
                    </div>

                    <div class="panel-body timeline-body">
                      <h5>Human-Computer Interaction (HCI)</h5>
                      <p>
                        University of Patras, Greece<br />
                        Departments of Computer Engineering and Informatics &amp; Electrical and Computer Engineering
                      </p>
                      <!-- <p><i class="fas fa-2x fa-fw fa-medal text-danger"></i> Awarded an <strong class="text-info">honorary diploma</strong> for the 2nd place in the competition for the <strong class="text-danger">best thesis project</strong></p> -->
                    </div>
                  </div>
                </div>
              </li>

              <li class="timeline-inverted">
                <div class="posted-date">
                  <span class="month">2017 - 2021</span>
                </div>

                <div id="edu-02" class="panel panel-success timeline-panel wow" data-wow-duration="1.0s">
                  <div class="timeline-content">

                    <div class="panel-heading timeline-heading row">
                      <div class="col-md-10 col-xs-9 pull-left">
                        <h3 class="panel-title pane">Bachelor's degree</h3>
                        <p class="text-primary"> - graduate diploma</p>
                      </div>

                      <div class="col-md-2 col-xs-3 pull-right text-center">
                        <i class="fas fa-3x fa-graduation-cap text-success"></i>
                      </div>
                    </div>

                    <div class="panel-body timeline-body">
                      <h5>Mathematics</h5>
                      <p>
                        University of Patras, Greece<br />
                        Department of Mathematics
                      </p>
                    </div><!--/ /timeline-body /-->
                  </div><!--/ /timeline-content /-->
                </div><!--/ /timeline-panel /-->
              </li><!--/ /timeline /-->

            </ul>
          </div>

        </div>
      </div><!--/ /row /-->

  <!--/  Skills  /-->
  <section id="skills" class="skills-section section-padding">
    <div class="container">
      <h2 class="section-title wow">Skills</h2>

      <div class="skill-chart text-center">
        <h3>Technical</h3>
      </div>

      <div class="row">

        <div class="col-md-6">

          <div class="skill-progress">
            <div class="skill-title">
              <i class="fab fa-2x fa-fw fa-html5"></i>
              <span>HTML5</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" role="progressbar">
                <span>85%</span>
              </div>
            </div>
          </div>

          <div class="skill-progress">
            <div class="skill-title">
              <i class="fab fa-2x fa-fw fa-css3-alt"></i>
              <span>CSS3</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" role="progressbar">
                <span>75%</span>
              </div>
            </div>
          </div>

          <div class="skill-progress">
              <div class="skill-title">
                <i class="fab fa-2x fa-fw fa-js"></i>
                <span>JavaScript</span>
              </div>
              <div class="progress">
                <div class="progress-bar six-sec-ease-in-out" aria-valuenow="79" aria-valuemin="0" aria-valuemax="100" role="progressbar">
                  <span>79%</span>
                </div>
              </div>
            </div>

          <div class="skill-progress">
            <div class="skill-title">
              <i class="fab fa-2x fa-fw fa-bootstrap"></i>
              <span>Bootstrap</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                <span>85%</span>
              </div>
            </div>
          </div>

          <div class="skill-progress">
            <div class="skill-title">
              <i class="fab fa-2x fa-fw fa-check fa-react"></i>
              <span>React</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                <span>80%</span>
              </div>
            </div>
          </div>

          <div class="skill-progress">
              <div class="skill-title">
                <i class="fab fa-2x fa-fw fa-figma"></i>
                <span>Figma</span>
              </div>
              <div class="progress">
                <div class="progress-bar six-sec-ease-in-out" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                  <span>90%</span>
                </div>
              </div>
            </div>
  
            <div class="skill-progress">
              <div class="skill-title">
                <i class="fab fa-2x fa-fw fa-balsamiq"></i>
                <span>Balsamiq</span>
              </div>
              <div class="progress">
                <div class="progress-bar six-sec-ease-in-out" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                  <span>85%</span>
                </div>
              </div>
            </div>

            <div class="skill-progress">
                <div class="skill-title">
                  <i class="fab fa-2x fa-fw fa-sketch"></i>
                  <span>Sketch</span>
                </div>
                <div class="progress">
                  <div class="progress-bar six-sec-ease-in-out" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                    <span>50%</span>
                  </div>
                </div>
              </div>
  
            <div class="skill-progress">
              <div class="skill-title">
                <i class="fas fa-2x fa-fw fa-shopping-cart fa-person"></i>
                <span>Creating personas/user stories</span>
              </div>
              <div class="progress">
                <div class="progress-bar six-sec-ease-in-out" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                  <span>90%</span>
                </div>
              </div>
            </div>

            <div class="skill-progress">
                <div class="skill-title">
                  <i class="fab fa-2x fa-fw fa-node-js"></i>
                  <span>Node.js</span>
                </div>
                <div class="progress">
                  <div class="progress-bar six-sec-ease-in-out" aria-valuenow="65" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                    <span>65%</span>
                  </div>
                </div>
              </div>

        </div><!--/ /.col-md-6 /-->

        <div class="col-md-6">

        <div class="skill-progress">
          <div class="skill-title">
            <i class="fab fa-2x fa-fw fa-node"></i>
            <span>Express</span>
          </div>
          <div class="progress">
            <div class="progress-bar six-sec-ease-in-out" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" role="progressbar">
              <span>70%</span>
            </div>
          </div>
        </div>

        <div class="skill-progress">
            <div class="skill-title">
              <i class="fas fa-2x fa-fw fa-cube fa-python"></i>
              <span>Python</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                <span>50%</span>
              </div>
            </div>
          </div>
          
          <div class="skill-progress">
              <div class="skill-title">
                  <i class="fa fa-2x fa-fw fa-hashtag"></i>
                  <span>Bash scripting</span>
                </div>
              <div class="progress">
                <div class="progress-bar six-sec-ease-in-out" aria-valuenow="79" aria-valuemin="0" aria-valuemax="100" role="progressbar">
                  <span>79%</span>
                </div>
              </div>
            </div>
  
          <div class="skill-progress">
            <div class="skill-title">
              <i class="fas fa-2x fa-fw fa-dice-d20 fa-c++"></i>
              <span>C++</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="45" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                <span>45%</span>
              </div>
            </div>
          </div>
  
          <div class="skill-progress">
            <div class="skill-title">
              <i class="fab fa-2x fa-fw fa-fortran"></i>
              <span>Fortran 95</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="49" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                <span>49%</span>
              </div>
            </div>
          </div>

          <div class="skill-progress">
            <div class="skill-title">
              <i class="fab fa-2x fa-fw fa-matlab"></i>
              <span>Matlab</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="69" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                <span>69%</span>
              </div>
            </div>
          </div>    
          
          <div class="skill-progress">
              <div class="skill-title">
                <i class="fab fa-2x fa-fw fa-latex"></i>
                <span>LaTex</span>
              </div>
              <div class="progress">
                <div class="progress-bar six-sec-ease-in-out" aria-valuenow="69" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                  <span>69%</span>
                </div>
              </div>
            </div> 

          <div class="skill-progress">
            <div class="skill-title">
              <i class="fab fa-2x fa-fw fa-postgresql"></i>
              <span>PostgreSQL</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="79" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                <span>79%</span>
              </div>
            </div>
          </div>

          <div class="skill-progress">
              <div class="skill-title">
                <i class="fab fa-2x fa-fw fa-firestore"></i>
                <span>Cloud Firestore firebase</span>
              </div>
              <div class="progress">
                <div class="progress-bar six-sec-ease-in-out" aria-valuenow="79" aria-valuemin="0" aria-valuemax="100" role="progressbar" >
                  <span>79%</span>
                </div>
              </div>
            </div>

          <div class="skill-progress">
            <div class="skill-title">
              <i class="fas fa-2x fa-fw fa-database fa-mysql"></i>
              <span>MySQL</span>
            </div>
            <div class="progress">
              <div class="progress-bar six-sec-ease-in-out" aria-valuenow="76" aria-valuemin="0" aria-valuemax="100" role="progressbar">
                <span>76%</span>
              </div>
            </div><!--/ /.progress /-->
          </div><!--/ /.skill-progress /-->

        </div><!--/ /.col-md-6 /-->

      </div><!--/ /.row /-->

      <div class="skill-chart text-center">
        <h3>Emotional</h3>
      </div>

      <div class="row more-skill text-center">

        <div class="col-xs-12 col-sm-6 col-md-3">
          <div class="chart" data-percent="80" data-color="e74c3c">
            <span class="percent"></span>
            <div class="chart-text">
              <span>Communication</span>
            </div>
          </div>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-3">
          <div class="chart" data-percent="85" data-color="2ecc71">
            <span class="percent"></span>
            <div class="chart-text">
              <span>Creativity</span>
            </div>
          </div>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-3">
          <div class="chart" data-percent="65" data-color="3498db">
            <span class="percent"></span>
            <div class="chart-text">
              <span>Leadership</span>
            </div>
          </div>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-3">
          <div class="chart" data-percent="85" data-color="3498db">
            <span class="percent"></span>
            <div class="chart-text">
              <span>Problem Solving</span>
            </div>
          </div>
        </div>

      </div>

    </div><!--/ /.container /-->
  </section><!--/ End Skills Section /-->


  <!--/  Portfolio  /-->
  <section id="portfolio" class="portfolio-section section-padding">
    <div class="container">

      <h2 class="section-title wow">Portfolio</h2>

      <ul class="list-inline" id="filter">
        <li><a data-group="all" class="active">All</a></li>
        <li><a data-group="crud">CRUD app</a></li>
        <li><a data-group="react">React app</a></li>
        <li><a data-group="figma">Figma mockups</a></li>
        <li><a data-group="balsamiq">Balsamiq mockups</a></li>
        <li><a data-group="thesis">Master Thesis</a></li>
        <li><a data-group="others">Others</a></li>
      </ul>

      <div class="row">
        <div id="og-grid" data-id="og-grid" class="og-grid">

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "crud"]'>
            <div class="portfolio-bg">
              <div class="portfolio">
                <div class="tt-overlay"></div>
                <div class="links">
                  <a target="_blank" rel="noopener" href="https://docs.google.com/document/d/1XQvIrsZJHy1N5csdu2hoiK0b1E0alsFNSVnF8DN6Xzc/edit"><i class="fas fa-file-pdf-o"></i></a>
                  <a target="_blank" rel="noopener" href="https://docs.google.com/presentation/d/1eeZBmvqlFSxtlEXojM9oOos3CNNYK4uOFlFwWFMIn0U/edit?usp=sharing"><i class="fas fa-file-powerpoint-o"></i></a>
                  <a target="_blank" rel="noopener" href="https://github.com/vournam/cookshare-project.git"><i class="fab fa-github"></i></a>
                  <a class="image-link" href="https://drive.google.com/uc?id=13RjixzqtUakoDZ8TjY7BGbJLhRS8l0L9"><i class="fa fa-search-plus"></i></a>
                </div>

                <picture>
                  <img src="https://drive.google.com/uc?id=13RjixzqtUakoDZ8TjY7BGbJLhRS8l0L9" alt="CRUD app with Bootstrap &amp; PostgreSQL" />
                </picture>

                <div class="portfolio-info">
                  <h3>CRUD cooking network web app with Bootstrap &amp; PostgreSQL</h3>
                </div>
              </div>
            </div>
          </div>

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "react"]'>
            <div class="portfolio-bg">
              <div class="portfolio">
                <div class="tt-overlay"></div>
                <div class="links">
                    <a target="_blank" rel="noopener" href="https://codesandbox.io/s/newflix-r463r6"><i class="fas fa-file-pdf-o"></i></a>
                  <a target="_blank" rel="noopener" href="https://r463r6.csb.app/"><i class="fas fa-play-circle"></i></a>
                  <a target="_blank" rel="noopener" href="https://github.com/vournam/Newflix-react-app.git"><i class="fab fa-github"></i></a>
                  <a class="image-link" href="https://drive.google.com/uc?id=1u1btfFga-zxFVHuRvZVy_gUDIqRq_iqN"><i class="fa fa-search-plus"></i></a>
                </div>

                <picture>
                  <img src="https://drive.google.com/uc?id=1u1btfFga-zxFVHuRvZVy_gUDIqRq_iqN" alt="React movie app" />
                </picture>

                <div class="portfolio-info">
                  <h3>React movie app</h3>
                </div>
              </div>
            </div>
          </div>

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "react"]'>
              <div class="portfolio-bg">
                <div class="portfolio">
                  <div class="tt-overlay"></div>
                  <div class="links">
                    <a target="_blank" rel="noopener" href="https://codesandbox.io/s/form-with-usestate-hook-kls5wz?file=/src/index.js:35-267"><i class="fas fa-file-pdf-o"></i></a>
                    <a target="_blank" rel="noopener" href="https://kls5wz.csb.app/"><i class="fas fa-play-circle"></i></a>
                    <a class="image-link" href="https://drive.google.com/uc?id=1WDH73xL_Z4DGBb8hPf5sxrmP5sy3qcUZ"><i class="fa fa-search-plus"></i></a>
                  </div>
  
                  <picture>
                    <img src="https://drive.google.com/uc?id=1WDH73xL_Z4DGBb8hPf5sxrmP5sy3qcUZ" alt="Vaccination Questionnaire" />
                  </picture>
  
                  <div class="portfolio-info">
                    <h3>Vaccination Questionnaire</h3>
                  </div>
                </div>
              </div>
            </div>

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "figma"]'>
            <div class="portfolio-bg">
              <div class="portfolio">
                <div class="tt-overlay"></div>

                <div class="links">
                  <a target="_blank" rel="noopener" href="https://docs.google.com/document/d/1107WdgaLWSnjkdXcgyGfMbo5U3gjYIdHwuN0FxX1LiM/edit"><i class="fas fa-file-pdf-o"></i></a>
                  <a target="_blank" rel="noopener" href="https://docs.google.com/presentation/d/12JLm_Ni_cAQZd0u5TJs78A75bWGP84Rdb363FX9rRCw/edit?usp=sharing"><i class="fas fa-file-powerpoint-o"></i></a>
                  <a target="_blank" rel="noopener" href="https://www.figma.com/file/UBhRqYqVzBUvsuiOx2uyqi/EduRobot"><i class="fas fa-play-circle"></i></a>
                  <a class="image-link" href="https://drive.google.com/uc?id=1pBrAb79zmlliWCzCFTErDuesDyn6g5da"><i class="fa fa-search-plus"></i></a>
                </div>

                <picture>
                  <img src="https://drive.google.com/uc?id=1pBrAb79zmlliWCzCFTErDuesDyn6g5da" alt="Tablet app for remote education of children via a 'telepresence robot'" />
                </picture>

                <div class="portfolio-info">
                  <h3>Tablet app for remote education of children via a 'telepresence robot'</h3>
                </div>

              </div>
            </div>
          </div>

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "balsamiq"]'>
            <div class="portfolio-bg">
              <div class="portfolio">
                <div class="tt-overlay"></div>
                <div class="links">
                  <a target="_blank" rel="noopener" href="https://docs.google.com/document/d/1n0B6vGAeUgU61UwNqq_L2aquP-4YhR2mRVAgJ0hfCuU/edit"><i class="fas fa-file-pdf-o"></i></a>
                  <a class="image-link" href="https://drive.google.com/uc?id=1yveD15md-gzXuQnHRB-8GLdUfm_zbCH9"><i class="fa fa-search-plus"></i></a>
                </div>

                <picture>
                  <img src="https://drive.google.com/uc?id=1yveD15md-gzXuQnHRB-8GLdUfm_zbCH9" alt="Mobile application for natural disasters" />
                </picture>

                <div class="portfolio-info">
                  <h3>Mobile application for natural disasters</h3>
                </div>
              </div>
            </div>
          </div>

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "thesis", "react", "figma"]'>
            <div class="portfolio-bg">
              <div class="portfolio">
                <div class="tt-overlay"></div>
                <div class="links">
                  <a target="_blank" rel="noopener" href="https://www.figma.com/file/w3S1XpzvF9R94hYMVz65b0/Pilot-study?type=design&node-id=0-1&t=xVLKb6woHBYXHg69-0"><i class="fas fa-play-circle"></i></a>
                  <a target="_blank" rel="noopener" href="https://github.com/vournam/smart-home-app.git"><i class="fab fa-github"></i></a>
                  <a class="image-link" href="https://drive.google.com/uc?id=12Gb7cYySTYNMIcDECL886L2JoqQ-2_JZ"><i class="fa fa-search-plus"></i></a>
                </div>

                <picture>
                  <img src="https://drive.google.com/uc?id=12Gb7cYySTYNMIcDECL886L2JoqQ-2_JZ" alt="Mobile Smart-home app with green nudges" />
                </picture>

                <div class="portfolio-info">
                  <h3>Mobile Smart-home app with green nudges</h3>
                </div>
              </div>
            </div>
          </div>

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "others"]'>
            <div class="portfolio-bg">
              <div class="portfolio">
                <div class="tt-overlay"></div>
                <div class="links">
                    <a target="_blank" rel="noopener" href="https://docs.google.com/presentation/d/1gc5XMIni23gPhIfuN4ufGoTFlt4vsSnYiecErL45fJ0/edit?usp=sharing"><i class="fas fa-file-powerpoint-o"></i></a>
                  <a class="image-link" href="https://drive.google.com/uc?id=1yq-TIVG6_AlVOxgJmbdoxLZFgALrsikQ"><i class="fa fa-search-plus"></i></a>
                </div>

                <picture>
                  <img src="https://drive.google.com/uc?id=1yq-TIVG6_AlVOxgJmbdoxLZFgALrsikQ" alt="Online CS:GO Skins Lottery" />
                </picture>

                <div class="portfolio-info">
                  <h3>User personas &amp; scenarios for a tablet remote education app</h3>
                </div>
              </div>
            </div>
          </div>

          <div class="portfolio-item col-xs-6 col-sm-4 col-md-3" data-groups='["all", "others"]'>
              <div class="portfolio-bg">
                <div class="portfolio">
                  <div class="tt-overlay"></div>
                  <div class="links">
                    <a target="_blank" rel="noopener" href="https://docs.google.com/presentation/d/1L2I_RgRC5OTx7c_oDXqvZKNnErDhCCDSZI3t4v_M4xk/edit?usp=sharing"><i class="fas fa-file-powerpoint-o"></i></a>
                    <a class="image-link" href="https://drive.google.com/uc?id=1m3ZBdZCssXeyGfXbqzgtAUQCGZIvwJwI"><i class="fa fa-search-plus"></i></a>
                  </div>
  
                  <picture>
                    <img src="https://drive.google.com/uc?id=1m3ZBdZCssXeyGfXbqzgtAUQCGZIvwJwI" alt="Interaction &amp; Interface Design of a Public laundry washing machine" />
                  </picture>
  
                  <div class="portfolio-info">
                    <h3>Interaction &amp; Interface Design of a Public laundry washing machine</h3>
                  </div>
                </div>
              </div>
            </div>

        </div><!--/ /#grid /-->
      </div><!--/ /.row /-->

    </div><!--/ /.container /-->
  </section><!--/ End Works Section /-->

  <!--/  Footer  /-->
  <footer class="footer-wrapper">
    <div class="container">
      <div class="row">
        <div class="hidden-xs col-sm-4 col-md-4">
          <div class="copyright text-left">
            <p class=""> <a href="{{author.url}}" target="_blank" rel="noopener">MIT Licensed</a></p>
          </div>
        </div>
        <div class="col-xs-10 col-sm-4 col-md-4">
          <div class="copyright text-center">
            2016-{{built.year}} &copy; {{person.name.full}}
          </div>
        </div>
        <div class="col-xs-2 col-sm-4 col-md-4">
          <div class="copyright text-right">
            <small class="hidden-xs">{{built.hash}}</small>
            <span class="hidden-xs label label-success label-sm">v{{version}}-b{{cntr}}</span>
            <small class="hidden-xs">{{built.date}}</small>
          </div>
        </div>
      </div>
    </div>
  </footer><!--/ End Footer Section /-->


  <!--/  Scroll-up  /-->
  <div class="scroll-up">
    <a href="#home"><i class="fa fa-angle-up"></i></a>
  </div>

  <!--/ TEST VARIABLES
  ========================================================================= /-->

  <!--/  Javascript files
  ========================================================================= /-->
  <!-- <script src="assets/js/lib/jquery.js"></script>
  <script src="assets/js/lib/bootstrap.js"></script>
  <script src="assets/js/lib/jquery.waypoints.js"></script>
  <script src="assets/js/lib/inview.js"></script>
  <script src="assets/js/lib/jquery.stellar.js"></script>
  <script src="assets/js/lib/jquery.sticky.js"></script>
  <script src="assets/js/lib/wow.js"></script>

  <script src="assets/js/lib/jquery.inview.js"></script>
  <script src="assets/js/lib/jquery.countTo.js"></script>
  <script src="assets/js/lib/jquery.easypiechart.js"></script> -->

  <!-- <script src="assets/js/plugins/modernizr.custom.js"></script> -->

  <!-- <script src="assets/js/lib/shuffle.js"></script>
  <script src="assets/js/lib/jquery.magnific-popup.js"></script>
  <script async src="assets/js/lib/smoothscroll.js"></script>
  <script defer src="assets/js/lib/jquery.noty.packaged.js"></script> -->
  <!-- <script defer src="assets/js/lib/bower-bundle.js"></script> -->

  <!--/  Javascript files
  ========================================================================= /-->
  <!-- <script async src="assets/js/lib/libs-bundle.js"></script> -->
  <script defer="defer" src="assets/js/lib/libs-bundle.js"></script>

  <!-- Load React -->
  <!-- Note: when deploying, replace "development.js" with "production.min.js" -->
  <!-- <script crossorigin src="https://unpkg.com/react@16/umd/react.development.js"></script> -->
  <!-- <script crossorigin src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script> -->

  <script defer="defer" src="assets/js/front/index.js"></script>
  <script defer="defer" src="assets/js/front/theme.js"></script>
  <!-- <script src="assets/js/front/theme.js"></script> -->
  <script src="assets/js/front/gmap.js"></script>

  <script async src="https://maps.googleapis.com/maps/api/js?v=3.exp&amp;key={{keys.google.maps}}&amp;callback=initMap"></script>

  <!-- <script>
    document.write('<script src="' + location.protocol + '//' + (location.host || 'localhost').split(':')[0] + ':35729/livereload.js?snipver=1"></' + 'script>');
  </script> -->

  <!--/ RequireJS
  ========================================================================= /-->
  <!--/ Require.js /-->
  <!-- <script src="assets/js/lib/require.js" data-main="assets/js/app-config-require.js"></script> -->

</body>
</html>
