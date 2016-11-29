



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-92d354668263723b226099d22b6ff9945593c2bfe41f4403b91481b735f484b0.css" integrity="sha256-ktNUZoJjcjsiYJnSK2/5lFWTwr/kH0QDuRSBtzX0hLA=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-62c11667b6474156face4798c12d179525fd089f1bf03bc0f367c843b5344a21.css" integrity="sha256-YsEWZ7ZHQVb6zkeYwS0XlSX9CJ8b8DvA82fIQ7U0SiE=" media="all" rel="stylesheet" />
    
    
    
    

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=device-width">
    
    <title>messenger-bot-tutorial/README.md at master · jw84/messenger-bot-tutorial</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="https://avatars2.githubusercontent.com/u/48764?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="jw84/messenger-bot-tutorial" name="twitter:title" /><meta content="messenger-bot-tutorial - Facebook Messenger bot 15 minute tutorial" name="twitter:description" />
      <meta content="https://avatars2.githubusercontent.com/u/48764?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="jw84/messenger-bot-tutorial" property="og:title" /><meta content="https://github.com/jw84/messenger-bot-tutorial" property="og:url" /><meta content="messenger-bot-tutorial - Facebook Messenger bot 15 minute tutorial" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MjQyMzYzODM6NzMyYzdjZGJjMzEwMjYyOTExYTFmNjgyNDJjYjkxYzI6ZjIxYzc4NjE1MmQ1ODdiYTMzM2QwODI0ODczNDBlMGM4MGM3OTdhZWIzYTA1ZWI3ODI1ZGIxYjdhMTQxZjcwYw==--c5bce0867eb587d98a09e4039e1137d5a4410352">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">
    <meta name="request-id" content="527A4E12:14AEC:1E8FBD9A:583CD1D9" data-pjax-transient>

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="527A4E12:14AEC:1E8FBD9A:583CD1D9" name="octolytics-dimension-request_id" /><meta content="24236383" name="octolytics-actor-id" /><meta content="Guraz" name="octolytics-actor-login" /><meta content="ead365ddc602a5ee5c558e0c90070f78dbef4057c78dc29765595845f9cab648" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="Guraz">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="YzdiMDdlYTBlOWNjNGI1ZGZjNmY2YTZiMTExMTc2OWZmZGZlYTk3ZGIxMWIwNDM3ZDZmYjZhMzEwNzY1YWMzY3x7InJlbW90ZV9hZGRyZXNzIjoiODIuMTIyLjc4LjE4IiwicmVxdWVzdF9pZCI6IjUyN0E0RTEyOjE0QUVDOjFFOEZCRDlBOjU4M0NEMUQ5IiwidGltZXN0YW1wIjoxNDgwMzgwODk0LCJob3N0IjoiZ2l0aHViLmNvbSJ9">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta name="html-safe-nonce" content="3d013f07e998ca76a94ccd4a4a78599047b6d101">
    <meta content="adba5687f40f1fed8217d22d7d261efd2a45743d" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="d6bcbe3a874fcfb8adbddfba81673948">
    

      
  <meta name="description" content="messenger-bot-tutorial - Facebook Messenger bot 15 minute tutorial">
  <meta name="go-import" content="github.com/jw84/messenger-bot-tutorial git https://github.com/jw84/messenger-bot-tutorial.git">

  <meta content="48764" name="octolytics-dimension-user_id" /><meta content="jw84" name="octolytics-dimension-user_login" /><meta content="56199482" name="octolytics-dimension-repository_id" /><meta content="jw84/messenger-bot-tutorial" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="56199482" name="octolytics-dimension-repository_network_root_id" /><meta content="jw84/messenger-bot-tutorial" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/jw84/messenger-bot-tutorial/commits/master.atom" rel="alternate" title="Recent Commits to messenger-bot-tutorial:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/jw84/messenger-bot-tutorial/blob/master/README.md" data-pjax-transient>
  </head>


  <body class="logged-in  env-production windows vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jw84/messenger-bot-tutorial/search" class="js-site-search-form" data-scoped-search-url="/jw84/messenger-bot-tutorial/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
      <div class="header-search-scope">This repository</div>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
    </label>
</form></div>


      <ul class="header-nav float-left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav float-right" id="user-links">
  <li class="header-nav-item">
    

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus float-left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="jw84/messenger-bot-tutorial">This repository</span>
  </div>
    <a class="dropdown-item" href="/jw84/messenger-bot-tutorial/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/Guraz"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@Guraz" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/24236383?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">Guraz</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/Guraz" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/Guraz?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="adba5687f40f1fed8217d22d7d261efd2a45743d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="L/dxciAzkckm9n60pmF0YNvngtoHcesqLD1C80tW/ka5BfkvaBrCnqbLXiWfI+AKOaidgsgpSDWsYKUtr+InhQ==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="adba5687f40f1fed8217d22d7d261efd2a45743d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="NGwDm/IS9YHr5nUraRE/e06X42q3w4/RWzlIgqVulmWinovGujum1mvbVbpQU6sRrNj8MnibLM7bZK9cQdpPpg==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="56199482" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/jw84/messenger-bot-tutorial/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/jw84/messenger-bot-tutorial/watchers"
            aria-label="58 users are watching this repository">
            58
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                      Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jw84/messenger-bot-tutorial/unstar" class="starred" data-form-nonce="adba5687f40f1fed8217d22d7d261efd2a45743d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="MPkJ0XgJbL5c0uX8W5b4v3d3iCWXNAuY0xBsLm/F8Y+mC4GMMCA/6dzvxW1i1GzVlTiXfVhsqIdTTYvwi3EoTA==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar jw84/messenger-bot-tutorial"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/jw84/messenger-bot-tutorial/stargazers"
           aria-label="1048 users starred this repository">
          1,048
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jw84/messenger-bot-tutorial/star" class="unstarred" data-form-nonce="adba5687f40f1fed8217d22d7d261efd2a45743d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="utxjjGCKtFCmh3vYfZz4dberg3lC7b8WlQvxRITGlDYsLuvRKKPnBya6W0lE3mwfVeScIY21HAkVVhaaYHJN9Q==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star jw84/messenger-bot-tutorial"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/jw84/messenger-bot-tutorial/stargazers"
           aria-label="1048 users starred this repository">
          1,048
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jw84/messenger-bot-tutorial/fork" class="btn-with-count" data-form-nonce="adba5687f40f1fed8217d22d7d261efd2a45743d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="DTzInCNwmE5k7dQ0JErPTclBsMOpsIrL5REFDydUVDKbzkDBa1nLGeTQ9KUdCFsnKw6vm2boKdRlTOLRw+CN8Q==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of jw84/messenger-bot-tutorial to your account"
                aria-label="Fork your own copy of jw84/messenger-bot-tutorial to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/jw84/messenger-bot-tutorial/network" class="social-count"
       aria-label="326 users forked this repository">
      326
    </a>
  </li>
</ul>

    <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/jw84" class="url fn" rel="author">jw84</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/jw84/messenger-bot-tutorial" data-pjax="#js-repo-pjax-container">messenger-bot-tutorial</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/jw84/messenger-bot-tutorial" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /jw84/messenger-bot-tutorial" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/jw84/messenger-bot-tutorial/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /jw84/messenger-bot-tutorial/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">13</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/jw84/messenger-bot-tutorial/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /jw84/messenger-bot-tutorial/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">7</span>
      <meta itemprop="position" content="3">
</a>  </span>

  <a href="/jw84/messenger-bot-tutorial/projects" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /jw84/messenger-bot-tutorial/projects">
    <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
    Projects
    <span class="counter">0</span>
</a>
    <a href="/jw84/messenger-bot-tutorial/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /jw84/messenger-bot-tutorial/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

  <a href="/jw84/messenger-bot-tutorial/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /jw84/messenger-bot-tutorial/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"/></svg>
    Pulse
</a>
  <a href="/jw84/messenger-bot-tutorial/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /jw84/messenger-bot-tutorial/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/jw84/messenger-bot-tutorial/blob/7781dfe6ee769f3ce083359fdbf214eebc373ee6/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:63b11350aaa488a02b665117e02217e9 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/jw84/messenger-bot-tutorial/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="BtnGroup float-right">
    <a href="/jw84/messenger-bot-tutorial/find/master"
          class="js-pjax-capture-input btn btn-sm BtnGroup-item"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/jw84/messenger-bot-tutorial"><span>messenger-bot-tutorial</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/jw84/messenger-bot-tutorial/commit/c22ca552d89b79fbcbe1f9aae9aacd38350be4ac" data-pjax>
          c22ca55
        </a>
        <relative-time datetime="2016-05-29T19:02:32Z">May 29, 2016</relative-time>
      </span>
      <div>
        <img alt="@thelostspore" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/3950085?v=3&amp;s=40" width="20" />
        <a href="/thelostspore" class="user-mention" rel="contributor">thelostspore</a>
          <a href="/jw84/messenger-bot-tutorial/commit/c22ca552d89b79fbcbe1f9aae9aacd38350be4ac" class="message" data-pjax="true" title="Config var section in README">Config var section in README</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>2</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="jw84" href="/jw84/messenger-bot-tutorial/commits/master/README.md?author=jw84"><img alt="@jw84" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/48764?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="thelostspore" href="/jw84/messenger-bot-tutorial/commits/master/README.md?author=thelostspore"><img alt="@thelostspore" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/3950085?v=3&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@jw84" height="24" src="https://avatars0.githubusercontent.com/u/48764?v=3&amp;s=48" width="24" />
            <a href="/jw84">jw84</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@thelostspore" height="24" src="https://avatars0.githubusercontent.com/u/3950085?v=3&amp;s=48" width="24" />
            <a href="/thelostspore">thelostspore</a>
          </li>
      </ul>
    </div>
  </div>


<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/jw84/messenger-bot-tutorial/raw/master/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/jw84/messenger-bot-tutorial/blame/master/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item">Blame</a>
      <a href="/jw84/messenger-bot-tutorial/commits/master/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/jw84/messenger-bot-tutorial?branch=master&amp;filepath=README.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jw84/messenger-bot-tutorial/edit/master/README.md" class="inline-form js-update-url-with-hash" data-form-nonce="adba5687f40f1fed8217d22d7d261efd2a45743d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="7lRmN8L8SH6HOxnPt1MuMgkjFgKH3x7Gfcm4D3Rdtjl4pu5qitUbKQcGOV6OEbpY62wJWkiHvdn9lF/RkOlv+g==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
</form>        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jw84/messenger-bot-tutorial/delete/master/README.md" class="inline-form" data-form-nonce="adba5687f40f1fed8217d22d7d261efd2a45743d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="7Iapm1ny251zeNmx9+UNoI4dX8yZTbS7DzZZXR05WeZ6dCHGEduIyvNF+SDOp5nKbFJAlFYVF6SPa76D+Y2AJQ==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      336 lines (254 sloc)
      <span class="file-info-divider"></span>
    10.5 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content--creating-your-own-facebook-messenger-bot" class="anchor" href="#-creating-your-own-facebook-messenger-bot" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><g-emoji alias="robot" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f916.png" ios-version="9.1">🤖</g-emoji> Creating your own Facebook Messenger bot</h1>

<p><a href="/jw84/messenger-bot-tutorial/blob/master/demo/Demo.gif" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/Demo.gif" alt="Alt text" style="max-width:100%;"></a></p>

<p>Facebook recently opened up their Messenger platform to enable bots to converse with users through Facebook Apps and on Facebook Pages. </p>

<p>You can read the  <a href="https://developers.facebook.com/docs/messenger-platform/quickstart">documentation</a> the Messenger team prepared but it's not very clear for beginners and intermediate hackers. </p>

<p>So instead here is how to create your own messenger bot in 15 minutes.</p>

<h2><a id="user-content--get-set" class="anchor" href="#-get-set" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><g-emoji alias="raised_hands" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f64c.png" ios-version="6.0">🙌</g-emoji> Get set</h2>

<p>Messenger bots uses a web server to process messages it receives or to figure out what messages to send. You also need to have the bot be authenticated to speak with the web server and the bot approved by Facebook to speak with the public.</p>

<p>You can also skip the whole thing by git cloning this repository, running npm install, and run a server somewhere.</p>

<h3><a id="user-content-build-the-server" class="anchor" href="#build-the-server" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><em>Build the server</em></h3>

<ol>
<li><p>Install the Heroku toolbelt from here <a href="https://toolbelt.heroku.com">https://toolbelt.heroku.com</a> to launch, stop and monitor instances. Sign up for free at <a href="https://www.heroku.com">https://www.heroku.com</a> if you don't have an account yet.</p></li>
<li><p>Install Node from here <a href="https://nodejs.org">https://nodejs.org</a>, this will be the server environment. Then open up Terminal or Command Line Prompt and make sure you've got the very most recent version of npm by installing it again:</p>

<pre><code>sudo npm install npm -g
</code></pre></li>
<li><p>Create a new folder somewhere and let's create a new Node project. Hit Enter to accept the defaults.</p>

<pre><code>npm init
</code></pre></li>
<li><p>Install the additional Node dependencies. Express is for the server, request is for sending out messages and body-parser is to process messages.</p>

<pre><code>npm install express request body-parser --save
</code></pre></li>
<li><p>Create an index.js file in the folder and copy this into it. We will start by authenticating the bot.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-s"><span class="pl-pds">'</span>use strict<span class="pl-pds">'</span></span>

<span class="pl-k">const</span> <span class="pl-c1">express</span> <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>express<span class="pl-pds">'</span></span>)
<span class="pl-k">const</span> <span class="pl-c1">bodyParser</span> <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>body-parser<span class="pl-pds">'</span></span>)
<span class="pl-k">const</span> <span class="pl-c1">request</span> <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>request<span class="pl-pds">'</span></span>)
<span class="pl-k">const</span> <span class="pl-c1">app</span> <span class="pl-k">=</span> <span class="pl-en">express</span>()

<span class="pl-smi">app</span>.<span class="pl-c1">set</span>(<span class="pl-s"><span class="pl-pds">'</span>port<span class="pl-pds">'</span></span>, (<span class="pl-c1">process</span>.<span class="pl-smi">env</span>.<span class="pl-c1">PORT</span> <span class="pl-k">||</span> <span class="pl-c1">5000</span>))

<span class="pl-c">// Process application/x-www-form-urlencoded</span>
<span class="pl-smi">app</span>.<span class="pl-en">use</span>(<span class="pl-smi">bodyParser</span>.<span class="pl-en">urlencoded</span>({extended<span class="pl-k">:</span> <span class="pl-c1">false</span>}))

<span class="pl-c">// Process application/json</span>
<span class="pl-smi">app</span>.<span class="pl-en">use</span>(<span class="pl-smi">bodyParser</span>.<span class="pl-en">json</span>())

<span class="pl-c">// Index route</span>
<span class="pl-smi">app</span>.<span class="pl-c1">get</span>(<span class="pl-s"><span class="pl-pds">'</span>/<span class="pl-pds">'</span></span>, <span class="pl-k">function</span> (<span class="pl-smi">req</span>, <span class="pl-smi">res</span>) {
    <span class="pl-smi">res</span>.<span class="pl-c1">send</span>(<span class="pl-s"><span class="pl-pds">'</span>Hello world, I am a chat bot<span class="pl-pds">'</span></span>)
})

<span class="pl-c">// for Facebook verification</span>
<span class="pl-smi">app</span>.<span class="pl-c1">get</span>(<span class="pl-s"><span class="pl-pds">'</span>/webhook/<span class="pl-pds">'</span></span>, <span class="pl-k">function</span> (<span class="pl-smi">req</span>, <span class="pl-smi">res</span>) {
    <span class="pl-k">if</span> (<span class="pl-smi">req</span>.<span class="pl-smi">query</span>[<span class="pl-s"><span class="pl-pds">'</span>hub.verify_token<span class="pl-pds">'</span></span>] <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>my_voice_is_my_password_verify_me<span class="pl-pds">'</span></span>) {
        <span class="pl-smi">res</span>.<span class="pl-c1">send</span>(<span class="pl-smi">req</span>.<span class="pl-smi">query</span>[<span class="pl-s"><span class="pl-pds">'</span>hub.challenge<span class="pl-pds">'</span></span>])
    }
    <span class="pl-smi">res</span>.<span class="pl-c1">send</span>(<span class="pl-s"><span class="pl-pds">'</span>Error, wrong token<span class="pl-pds">'</span></span>)
})

<span class="pl-c">// Spin up the server</span>
<span class="pl-smi">app</span>.<span class="pl-en">listen</span>(<span class="pl-smi">app</span>.<span class="pl-c1">get</span>(<span class="pl-s"><span class="pl-pds">'</span>port<span class="pl-pds">'</span></span>), <span class="pl-k">function</span>() {
    <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>running on port<span class="pl-pds">'</span></span>, <span class="pl-smi">app</span>.<span class="pl-c1">get</span>(<span class="pl-s"><span class="pl-pds">'</span>port<span class="pl-pds">'</span></span>))
})</pre></div></li>
<li><p>Make a file called Procfile and copy this. This is so Heroku can know what file to run.</p>

<pre><code>web: node index.js
</code></pre></li>
<li><p>Commit all the code with Git then create a new Heroku instance and push the code to the cloud.</p>

<pre><code>git init
git add .
git commit --message 'hello world'
heroku create
git push heroku master
</code></pre></li>
</ol>

<h3><a id="user-content-setup-the-facebook-app" class="anchor" href="#setup-the-facebook-app" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><em>Setup the Facebook App</em></h3>

<ol>
<li><p>Create or configure a Facebook App or Page here <a href="https://developers.facebook.com/apps/">https://developers.facebook.com/apps/</a></p>

<p><a href="/jw84/messenger-bot-tutorial/blob/master/demo/shot1.jpg" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/shot1.jpg" alt="Alt text" style="max-width:100%;"></a></p></li>
<li><p>In the app go to Messenger tab then click Setup Webhook. Here you will put in the URL of your Heroku server and a token. Make sure to check all the subscription fields. </p>

<p><a href="/jw84/messenger-bot-tutorial/blob/master/demo/shot3.jpg" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/shot3.jpg" alt="Alt text" style="max-width:100%;"></a></p></li>
<li><p>Get a Page Access Token and save this somewhere. </p>

<p><a href="/jw84/messenger-bot-tutorial/blob/master/demo/shot2.jpg" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/shot2.jpg" alt="Alt text" style="max-width:100%;"></a></p></li>
<li><p>Go back to Terminal and type in this command to trigger the Facebbook app to send messages. Remember to use the token you requested earlier.</p>

<div class="highlight highlight-source-shell"><pre>curl -X POST <span class="pl-s"><span class="pl-pds">"</span>https://graph.facebook.com/v2.6/me/subscribed_apps?access_token=&lt;PAGE_ACCESS_TOKEN&gt;<span class="pl-pds">"</span></span></pre></div></li>
</ol>

<h3><a id="user-content-setup-the-bot" class="anchor" href="#setup-the-bot" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><em>Setup the bot</em></h3>

<p>Now that Facebook and Heroku can talk to each other we can code out the bot.</p>

<ol>
<li><p>Add an API endpoint to index.js to process messages. Remember to also include the token we got earlier. </p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi">app</span>.<span class="pl-en">post</span>(<span class="pl-s"><span class="pl-pds">'</span>/webhook/<span class="pl-pds">'</span></span>, <span class="pl-k">function</span> (<span class="pl-smi">req</span>, <span class="pl-smi">res</span>) {
    <span class="pl-k">let</span> messaging_events <span class="pl-k">=</span> <span class="pl-smi">req</span>.<span class="pl-c1">body</span>.<span class="pl-smi">entry</span>[<span class="pl-c1">0</span>].<span class="pl-smi">messaging</span>
    <span class="pl-k">for</span> (<span class="pl-k">let</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> <span class="pl-smi">messaging_events</span>.<span class="pl-c1">length</span>; i<span class="pl-k">++</span>) {
        <span class="pl-k">let</span> <span class="pl-c1">event</span> <span class="pl-k">=</span> <span class="pl-smi">req</span>.<span class="pl-c1">body</span>.<span class="pl-smi">entry</span>[<span class="pl-c1">0</span>].<span class="pl-smi">messaging</span>[i]
        <span class="pl-k">let</span> sender <span class="pl-k">=</span> <span class="pl-c1">event</span>.<span class="pl-smi">sender</span>.<span class="pl-c1">id</span>
        <span class="pl-k">if</span> (<span class="pl-c1">event</span>.<span class="pl-smi">message</span> <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">event</span>.<span class="pl-smi">message</span>.<span class="pl-c1">text</span>) {
            <span class="pl-k">let</span> text <span class="pl-k">=</span> <span class="pl-c1">event</span>.<span class="pl-smi">message</span>.<span class="pl-c1">text</span>
            <span class="pl-en">sendTextMessage</span>(sender, <span class="pl-s"><span class="pl-pds">"</span>Text received, echo: <span class="pl-pds">"</span></span> <span class="pl-k">+</span> <span class="pl-smi">text</span>.<span class="pl-c1">substring</span>(<span class="pl-c1">0</span>, <span class="pl-c1">200</span>))
        }
    }
    <span class="pl-smi">res</span>.<span class="pl-en">sendStatus</span>(<span class="pl-c1">200</span>)
})

<span class="pl-k">const</span> <span class="pl-c1">token</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>&lt;PAGE_ACCESS_TOKEN&gt;<span class="pl-pds">"</span></span></pre></div>

<p><strong>Optional, but recommended</strong>: keep your app secrets out of version control!</p>

<ul>
<li>On Heroku, its easy to create dynamic runtime variables (known as <a href="https://devcenter.heroku.com/articles/config-vars">config vars</a>). This can be done in the Heroku dashboard UI for your app <strong>or</strong> from the command line:
<a href="/jw84/messenger-bot-tutorial/blob/master/demo/config_vars.jpg" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/config_vars.jpg" alt="Alt text" style="max-width:100%;"></a></li>
</ul>

<div class="highlight highlight-source-shell"><pre>heroku config:<span class="pl-c1">set</span> FB_PAGE_ACCESS_TOKEN=fake-access-token-dhsa09uji4mlkasdfsd

<span class="pl-c"># view</span>
heroku config</pre></div>

<ul>
<li>For local development: create an <a href="https://en.wikipedia.org/wiki/Environment_variable">environmental variable</a> in your current session or add to your shell config file.</li>
</ul>

<div class="highlight highlight-source-shell"><pre><span class="pl-c"># create env variable for current shell session</span>
<span class="pl-k">export</span> FB_PAGE_ACCESS_TOKEN=fake-access-token-dhsa09uji4mlkasdfsd

<span class="pl-c"># alternatively, you can add this line to your shell config</span>
<span class="pl-c"># export FB_PAGE_ACCESS_TOKEN=fake-access-token-dhsa09uji4mlkasdfsd</span>

<span class="pl-c1">echo</span> <span class="pl-smi">$FB_PAGE_ACCESS_TOKEN</span></pre></div>

<ul>
<li><code>config var</code> access at runtime</li>
</ul>

<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-c1">token</span> <span class="pl-k">=</span> <span class="pl-c1">process</span>.<span class="pl-smi">env</span>.<span class="pl-c1">FB_PAGE_ACCESS_TOKEN</span></pre></div></li>
<li><p>Add a function to echo back messages</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">sendTextMessage</span>(<span class="pl-smi">sender</span>, <span class="pl-smi">text</span>) {
    <span class="pl-k">let</span> messageData <span class="pl-k">=</span> { text<span class="pl-k">:</span>text }
    <span class="pl-en">request</span>({
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>https://graph.facebook.com/v2.6/me/messages<span class="pl-pds">'</span></span>,
        qs<span class="pl-k">:</span> {access_token<span class="pl-k">:</span>token},
        method<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>POST<span class="pl-pds">'</span></span>,
        json<span class="pl-k">:</span> {
            recipient<span class="pl-k">:</span> {id<span class="pl-k">:</span>sender},
            message<span class="pl-k">:</span> messageData,
        }
    }, <span class="pl-k">function</span>(<span class="pl-smi">error</span>, <span class="pl-smi">response</span>, <span class="pl-smi">body</span>) {
        <span class="pl-k">if</span> (error) {
            <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>Error sending messages: <span class="pl-pds">'</span></span>, error)
        } <span class="pl-k">else</span> <span class="pl-k">if</span> (<span class="pl-smi">response</span>.<span class="pl-c1">body</span>.<span class="pl-smi">error</span>) {
            <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>Error: <span class="pl-pds">'</span></span>, <span class="pl-smi">response</span>.<span class="pl-c1">body</span>.<span class="pl-smi">error</span>)
        }
    })
}</pre></div></li>
<li><p>Commit the code again and push to Heroku</p>

<pre><code>git add .
git commit -m 'updated the bot to speak'
git push heroku master
</code></pre></li>
<li><p>Go to the Facebook Page and click on Message to start chatting!</p></li>
</ol>

<p><a href="/jw84/messenger-bot-tutorial/blob/master/demo/shot4.jpg" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/shot4.jpg" alt="Alt text" style="max-width:100%;"></a></p>

<h2><a id="user-content--customize-what-the-bot-says" class="anchor" href="#-customize-what-the-bot-says" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><g-emoji alias="gear" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2699.png" ios-version="9.1">⚙</g-emoji> Customize what the bot says</h2>

<h3><a id="user-content-send-a-structured-message" class="anchor" href="#send-a-structured-message" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><em>Send a Structured Message</em></h3>

<p>Facebook Messenger can send messages structured as cards or buttons. </p>

<p><a href="/jw84/messenger-bot-tutorial/blob/master/demo/shot5.jpg" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/shot5.jpg" alt="Alt text" style="max-width:100%;"></a></p>

<ol>
<li><p>Copy the code below to index.js to send an test message back as two cards.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">sendGenericMessage</span>(<span class="pl-smi">sender</span>) {
    <span class="pl-k">let</span> messageData <span class="pl-k">=</span> {
        <span class="pl-s"><span class="pl-pds">"</span>attachment<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
            <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>template<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>payload<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
                <span class="pl-s"><span class="pl-pds">"</span>template_type<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>generic<span class="pl-pds">"</span></span>,
                <span class="pl-s"><span class="pl-pds">"</span>elements<span class="pl-pds">"</span></span><span class="pl-k">:</span> [{
                    <span class="pl-s"><span class="pl-pds">"</span>title<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>First card<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>subtitle<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Element #1 of an hscroll<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>image_url<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>http://messengerdemo.parseapp.com/img/rift.png<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>buttons<span class="pl-pds">"</span></span><span class="pl-k">:</span> [{
                        <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>web_url<span class="pl-pds">"</span></span>,
                        <span class="pl-s"><span class="pl-pds">"</span>url<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>https://www.messenger.com<span class="pl-pds">"</span></span>,
                        <span class="pl-s"><span class="pl-pds">"</span>title<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>web url<span class="pl-pds">"</span></span>
                    }, {
                        <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>postback<span class="pl-pds">"</span></span>,
                        <span class="pl-s"><span class="pl-pds">"</span>title<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Postback<span class="pl-pds">"</span></span>,
                        <span class="pl-s"><span class="pl-pds">"</span>payload<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Payload for first element in a generic bubble<span class="pl-pds">"</span></span>,
                    }],
                }, {
                    <span class="pl-s"><span class="pl-pds">"</span>title<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Second card<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>subtitle<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Element #2 of an hscroll<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>image_url<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>http://messengerdemo.parseapp.com/img/gearvr.png<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>buttons<span class="pl-pds">"</span></span><span class="pl-k">:</span> [{
                        <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>postback<span class="pl-pds">"</span></span>,
                        <span class="pl-s"><span class="pl-pds">"</span>title<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Postback<span class="pl-pds">"</span></span>,
                        <span class="pl-s"><span class="pl-pds">"</span>payload<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Payload for second element in a generic bubble<span class="pl-pds">"</span></span>,
                    }],
                }]
            }
        }
    }
    <span class="pl-en">request</span>({
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>https://graph.facebook.com/v2.6/me/messages<span class="pl-pds">'</span></span>,
        qs<span class="pl-k">:</span> {access_token<span class="pl-k">:</span>token},
        method<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>POST<span class="pl-pds">'</span></span>,
        json<span class="pl-k">:</span> {
            recipient<span class="pl-k">:</span> {id<span class="pl-k">:</span>sender},
            message<span class="pl-k">:</span> messageData,
        }
    }, <span class="pl-k">function</span>(<span class="pl-smi">error</span>, <span class="pl-smi">response</span>, <span class="pl-smi">body</span>) {
        <span class="pl-k">if</span> (error) {
            <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>Error sending messages: <span class="pl-pds">'</span></span>, error)
        } <span class="pl-k">else</span> <span class="pl-k">if</span> (<span class="pl-smi">response</span>.<span class="pl-c1">body</span>.<span class="pl-smi">error</span>) {
            <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>Error: <span class="pl-pds">'</span></span>, <span class="pl-smi">response</span>.<span class="pl-c1">body</span>.<span class="pl-smi">error</span>)
        }
    })
}</pre></div></li>
<li><p>Update the webhook API to look for special messages to trigger the cards</p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi">app</span>.<span class="pl-en">post</span>(<span class="pl-s"><span class="pl-pds">'</span>/webhook/<span class="pl-pds">'</span></span>, <span class="pl-k">function</span> (<span class="pl-smi">req</span>, <span class="pl-smi">res</span>) {
    <span class="pl-k">let</span> messaging_events <span class="pl-k">=</span> <span class="pl-smi">req</span>.<span class="pl-c1">body</span>.<span class="pl-smi">entry</span>[<span class="pl-c1">0</span>].<span class="pl-smi">messaging</span>
    <span class="pl-k">for</span> (<span class="pl-k">let</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> <span class="pl-smi">messaging_events</span>.<span class="pl-c1">length</span>; i<span class="pl-k">++</span>) {
        <span class="pl-k">let</span> <span class="pl-c1">event</span> <span class="pl-k">=</span> <span class="pl-smi">req</span>.<span class="pl-c1">body</span>.<span class="pl-smi">entry</span>[<span class="pl-c1">0</span>].<span class="pl-smi">messaging</span>[i]
        <span class="pl-k">let</span> sender <span class="pl-k">=</span> <span class="pl-c1">event</span>.<span class="pl-smi">sender</span>.<span class="pl-c1">id</span>
        <span class="pl-k">if</span> (<span class="pl-c1">event</span>.<span class="pl-smi">message</span> <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">event</span>.<span class="pl-smi">message</span>.<span class="pl-c1">text</span>) {
            <span class="pl-k">let</span> text <span class="pl-k">=</span> <span class="pl-c1">event</span>.<span class="pl-smi">message</span>.<span class="pl-c1">text</span>
            <span class="pl-k">if</span> (text <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>Generic<span class="pl-pds">'</span></span>) {
                <span class="pl-en">sendGenericMessage</span>(sender)
                <span class="pl-k">continue</span>
            }
            <span class="pl-en">sendTextMessage</span>(sender, <span class="pl-s"><span class="pl-pds">"</span>Text received, echo: <span class="pl-pds">"</span></span> <span class="pl-k">+</span> <span class="pl-smi">text</span>.<span class="pl-c1">substring</span>(<span class="pl-c1">0</span>, <span class="pl-c1">200</span>))
        }
    }
    <span class="pl-smi">res</span>.<span class="pl-en">sendStatus</span>(<span class="pl-c1">200</span>)
})</pre></div></li>
</ol>

<h3><a id="user-content-act-on-what-the-user-messages" class="anchor" href="#act-on-what-the-user-messages" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><em>Act on what the user messages</em></h3>

<p>What happens when the user clicks on a message button or card though? Let's update the webhook API one more time to send back a postback function.</p>

<div class="highlight highlight-source-js"><pre>  <span class="pl-smi">app</span>.<span class="pl-en">post</span>(<span class="pl-s"><span class="pl-pds">'</span>/webhook/<span class="pl-pds">'</span></span>, <span class="pl-k">function</span> (<span class="pl-smi">req</span>, <span class="pl-smi">res</span>) {
    <span class="pl-k">let</span> messaging_events <span class="pl-k">=</span> <span class="pl-smi">req</span>.<span class="pl-c1">body</span>.<span class="pl-smi">entry</span>[<span class="pl-c1">0</span>].<span class="pl-smi">messaging</span>
    <span class="pl-k">for</span> (<span class="pl-k">let</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> <span class="pl-smi">messaging_events</span>.<span class="pl-c1">length</span>; i<span class="pl-k">++</span>) {
      <span class="pl-k">let</span> <span class="pl-c1">event</span> <span class="pl-k">=</span> <span class="pl-smi">req</span>.<span class="pl-c1">body</span>.<span class="pl-smi">entry</span>[<span class="pl-c1">0</span>].<span class="pl-smi">messaging</span>[i]
      <span class="pl-k">let</span> sender <span class="pl-k">=</span> <span class="pl-c1">event</span>.<span class="pl-smi">sender</span>.<span class="pl-c1">id</span>
      <span class="pl-k">if</span> (<span class="pl-c1">event</span>.<span class="pl-smi">message</span> <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">event</span>.<span class="pl-smi">message</span>.<span class="pl-c1">text</span>) {
        <span class="pl-k">let</span> text <span class="pl-k">=</span> <span class="pl-c1">event</span>.<span class="pl-smi">message</span>.<span class="pl-c1">text</span>
        <span class="pl-k">if</span> (text <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>Generic<span class="pl-pds">'</span></span>) {
            <span class="pl-en">sendGenericMessage</span>(sender)
            <span class="pl-k">continue</span>
        }
        <span class="pl-en">sendTextMessage</span>(sender, <span class="pl-s"><span class="pl-pds">"</span>Text received, echo: <span class="pl-pds">"</span></span> <span class="pl-k">+</span> <span class="pl-smi">text</span>.<span class="pl-c1">substring</span>(<span class="pl-c1">0</span>, <span class="pl-c1">200</span>))
      }
      <span class="pl-k">if</span> (<span class="pl-c1">event</span>.<span class="pl-smi">postback</span>) {
        <span class="pl-k">let</span> text <span class="pl-k">=</span> <span class="pl-c1">JSON</span>.<span class="pl-en">stringify</span>(<span class="pl-c1">event</span>.<span class="pl-smi">postback</span>)
        <span class="pl-en">sendTextMessage</span>(sender, <span class="pl-s"><span class="pl-pds">"</span>Postback received: <span class="pl-pds">"</span></span><span class="pl-k">+</span><span class="pl-smi">text</span>.<span class="pl-c1">substring</span>(<span class="pl-c1">0</span>, <span class="pl-c1">200</span>), token)
        <span class="pl-k">continue</span>
      }
    }
    <span class="pl-smi">res</span>.<span class="pl-en">sendStatus</span>(<span class="pl-c1">200</span>)
  })</pre></div>

<p>Git add, commit, and push to Heroku again.</p>

<p>Now when you chat with the bot and type 'Generic' you can see this.</p>

<p><a href="/jw84/messenger-bot-tutorial/blob/master/demo/shot6.jpg" target="_blank"><img src="/jw84/messenger-bot-tutorial/raw/master/demo/shot6.jpg" alt="Alt text" style="max-width:100%;"></a></p>

<h2><a id="user-content--how-to-share-your-bot" class="anchor" href="#-how-to-share-your-bot" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><g-emoji alias="satellite" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4e1.png" ios-version="6.0">📡</g-emoji> How to share your bot</h2>

<h3><a id="user-content-add-a-chat-button-to-your-webpage" class="anchor" href="#add-a-chat-button-to-your-webpage" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><em>Add a chat button to your webpage</em></h3>

<p>Go <a href="https://developers.facebook.com/docs/messenger-platform/plugin-reference">here</a> to learn how to add a chat button your page.</p>

<h3><a id="user-content-create-a-shortlink" class="anchor" href="#create-a-shortlink" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><em>Create a shortlink</em></h3>

<p>You can use <a href="https://m.me/">https://m.me/</a> to have someone start a chat.</p>

<h2><a id="user-content--whats-next" class="anchor" href="#-whats-next" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><g-emoji alias="bulb" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4a1.png" ios-version="6.0">💡</g-emoji> What's next?</h2>

<p>You can learn how to get your bot approved for public use <a href="https://developers.facebook.com/docs/messenger-platform/app-review">here</a>.</p>

<p>You can also connect an AI brain to your bot <a href="https://wit.ai">here</a></p>

<p>Read about all things chat bots with the ChatBots Magazine <a href="https://medium.com/chat-bots">here</a></p>

<p>You can also design Messenger bots in Sketch with the <a href="https://bots.mockuuups.com">Bots UI Kit</a>!</p>

<h2><a id="user-content-how-i-can-help" class="anchor" href="#how-i-can-help" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>How I can help</h2>

<p>I build and design bots all day. Email me for help!</p>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links float-right">
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.13445s from github-fe127-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
      </button>
      You can't perform that action at this time.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-fjanzKa4+830KgspYm1AVfW3AW7BlFuO/ZxrAUZgpuY=" src="https://assets-cdn.github.com/assets/frameworks-7e36a7cca6b8fbcdf42a0b29626d4055f5b7016ec1945b8efd9c6b014660a6e6.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-UM4bMmYIsfMYYg+C2/wdes3sB5OX+MUIZbtRJ76vXqk=" src="https://assets-cdn.github.com/assets/github-50ce1b326608b1f318620f82dbfc1d7acdec079397f8c50865bb5127beaf5ea9.js"></script>
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>

  </body>
</html>

