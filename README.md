		
<?xml  version ="1.0" encoding="UTF-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
   "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <b:include data='blog' name='all-head-content'/>
    <title><data:blog.pageTitle/></title>
    <b:skin><![CDATA[/*

   ====================
   <Variable name="bgcolor" description="Page Background Color"
             type="color" default="#ffffff" value="#ffffff">
   <Variable name="textcolor" description="Text Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="linkcolor" description="Link Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="pagetitlecolor" description="Blog Title Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="descriptioncolor" description="Blog Description Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="titlecolor" description="Post Title Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="bordercolor" description="Border Color"
             type="color" default="#DDFFDD" value="#DDFFDD">
   <Variable name="sidebarcolor" description="Sidebar Title Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="sidebartextcolor" description="Sidebar Text Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="visitedlinkcolor" description="Visited Link Color"
             type="color" default="#FF4422" value="#FF4422">
   <Variable name="bodyfont" description="Text Font"
             type="font" default="normal normal 100% Arial, verdana" value="normal normal 100% Arial, verdana">
   <Variable name="headerfont" description="Sidebar Title Font"
             type="font"
             default="normal normal 78% Arial, Verdana" value="normal normal 78% Arial, Verdana">
   <Variable name="pagetitlefont" description="Blog Title Font"
             type="font"
             default="normal normal 200% Arial, Verdana" value="normal normal 200% Arial, Verdana">
   <Variable name="descriptionfont" description="Blog Description Font"
             type="font"
             default="normal normal 78% Arial, verdana" value="normal normal 78% Arial, verdana">
   <Variable name="postfooterfont" description="Post Footer Font"
             type="font"
             default="normal normal 78% Arial, verdana" value="normal normal 78% Arial, verdana">
*/

/* Use this with templates/template-twocol.html --*/


<img src="http://content.pimp-my-profile.com/i81/9/9/1/f_be69c2ba04.jpg"> 

body {
  background:$bgcolor;
  margin:0;
  color:$textcolor;
  font:x-small $bodyfont;
  font-size/* */:/**/small;
  font-size: /**/small;
  text-align: center;
  background-color         : $bgcolor;
  background-image         : url() ;
  background-position      : Center Center; 
  background-attachment    : fixed ;
  background-repeat        : repeat ;
  border-color             : #DDFFDD ;
  border-width             : 0 px;
  border-style 	           : Solid ;
  scrollbar-face-color     : #000000 ;
  scrollbar-highlight-color: #bbbbbb ;
  scrollbar-3dlight-color  : #888888 ;
  scrollbar-shadow-color   : #555555 ;
  scrollbar-darkshadow-color: #333333 ;
  scrollbar-arrow-color    : #ffffff ;
  scrollbar-track-color    : #000000 ;
  }
a:link {
  color:$linkcolor;
  text-decoration:none;
  }
a:visited {
  color:$linkcolor;
  text-decoration:none;
  }
a:hover {
  color:$titlecolor;
  text-decoration:underline;
}
a img {
  border-width:0;
  }

/* Header
-----------------------------------------------
 */

#header-wrapper {
  width:660px;
  margin:0 auto 10px;
  border:1px solid $bordercolor;

  }

#header-inner {
  background-position: center;
  margin-left: auto;
  margin-right: auto;
}

#header { 
  margin: 5px;
  border: 1px solid $bordercolor;
  text-align: center;
  color:$pagetitlecolor;
  background-color:#transparent;
  background-image:url(none);
}

#header h1 {
  margin:5px 5px 0;
  padding:15px 20px .25em;
  line-height:1.2em;
  text-transform:uppercase;
  letter-spacing:.2em;
  font: $pagetitlecolor;
}

#header a {
  color:$pagetitlecolor;
  text-decoration:none;
  }

#header a:hover {
  color:$pagetitlecolor;
  }

#header .description {
  margin:0 5px 5px;
  padding:0 20px 15px;
  max-width:700px;
  text-transform:uppercase;
  letter-spacing:.2em;
  line-height: 1.4em;
  font: $bodyfont;
  color: $textcolor;
 }

#header img {
  margin-left: auto;
  margin-right: auto;
}


/* Outer-Wrapper
----------------------------------------------- */
#outer-wrapper {
  width: 660px;
  margin:0 auto;
  padding:10px;
  text-align:left;
  font: $bodyfont;
  }

#main-wrapper {
  width: 410px;
  float: left;
  padding: 5px;
  border:1px solid $bordercolor;
  background-color:#transparent;
  background-image:url(none);

  word-wrap: break-word; /* fix for long text breaking sidebar float in IE */
  overflow: hidden;     /* fix for long non-text content breaking IE sidebar float */
  }

#sidebar-wrapper {
  width: 220px;
  float: right;
  padding: 5px;
  border:1px solid $bordercolor;
  background-color:#transparent;
  background-image:url(none);

  word-wrap: break-word; /* fix for long text breaking sidebar float in IE */
  overflow: hidden;      /* fix for long non-text content breaking IE sidebar float */
}


/* Headings
----------------------------------------------- */

h2 {
  margin:1.5em 0 .75em;
  font:$headerfont;
  line-height: 1.4em;
  text-transform:uppercase;
  letter-spacing:.2em;
  color:$pagetitlecolor;
}


/* Posts
-----------------------------------------------
 */
h2.date-header {
  margin:1.5em 0 .5em;
  }

.post {
  margin:.5em 0 1.5em;
  border-bottom:1px dotted $bordercolor;
  padding-bottom:1.5em;
  background-color:transparent;
  }
.post h3 {
  margin:.25em 0 0;
  padding:0 0 4px;
  font-size:140%;
  font-weight:normal;
  line-height:1.4em;
  color:$pagetitlecolor;
}

.post h3 a, .post h3 a:visited, .post h3 strong {
  display:block;
  text-decoration:none;
  color:$titlecolor;
  font-weight:normal;
}

.post h3 strong, .post h3 a:hover {
  color:$textcolor;
}

.post p {
  margin:0 0 .75em;
  line-height:1.6em;
}

.post-footer {
  margin: .75em 0;
  color:$textcolor;
  text-transform:uppercase;
  letter-spacing:.1em;
  font: $bodyfont;
  line-height: 1.4em;
}

.comment-link {
  margin-left:.6em;
  }
.post img {
  padding:4px;
  border:1px solid $bordercolor;
  }
.post blockquote {
  margin:1em 20px;
  }
.post blockquote p {
  margin:.75em 0;
  }

/* Comments
----------------------------------------------- */
#comments h4 {
  margin:1em 0;
  font-weight: bold;
  line-height: 1.4em;
  text-transform:uppercase;
  letter-spacing:.2em;
  color: $textcolor;
  padding: 5px;
  border:1px solid $bordercolor;
  background-color:#transparent;
  background-image:url(none);

  }

#comments-block {
  margin:1em 0 1.5em;
  line-height:1.6em;
  }
#comments-block .comment-author {
  margin:.5em 0;
  }
#comments-block .comment-body {
  margin:.25em 0 0;
  }
#comments-block .comment-footer {
  margin:-.25em 0 2em;
  line-height: 1.4em;
  text-transform:uppercase;
  letter-spacing:.1em;
  }
#comments-block .comment-body p {
  margin:0 0 .75em;
  }
.deleted-comment {
  font-style:italic;
  color:gray;
  }

#blog-pager-newer-link {
  float: left;
 }
 
#blog-pager-older-link {
  float: right;
 }

#blog-pager { 
  text-align: center;
 }

.feed-links {
  clear: both;
  line-height: 2.5em;
}

/* Sidebar Content
----------------------------------------------- */
.sidebar { 
  color: $textcolor;
  line-height: 1.5em;
 }

.sidebar ul {
  list-style:none;
  margin:0 0 0;
  padding:0 0 0;
}
.sidebar li {
  margin:0;
  padding:0 0 .25em 15px;
  text-indent:-15px;
  line-height:1.5em;
  }

.sidebar .widget, .main .widget { 
  border-bottom:1px dotted $bordercolor;
  margin:0 0 1.5em;
  padding:0 0 1.5em;
 }

.main .Blog { 
  border-bottom-width: 0;
}


/* Profile 
----------------------------------------------- */
.profile-img { 
  float: left;
  margin: 0 5px 5px 0;
  padding: 4px;
  border: 1px solid $bordercolor;
}

.profile-data {
  margin:0;
  text-transform:uppercase;
  letter-spacing:.1em;
  font: $bodyfont;
  color: $textcolor;
  font-weight: bold;
  line-height: 1.6em;
}

.profile-datablock { 
  margin:.5em 0 .5em;
}

.profile-textblock { 
  margin: 0.5em 0;
  line-height: 1.6em;
}

.profile-link { 
  font: $bodyfont;
  text-transform: uppercase;
  letter-spacing: .1em;
}

/* Footer
----------------------------------------------- */
#footer {
  width:660px;
  clear:both;
  margin:0 auto;
  padding-top:15px;
  line-height: 1.6em;
  text-transform:uppercase;
  letter-spacing:.1em;
  text-align: center;
  padding: 5px;
  border:1px solid $bordercolor;
  background-color:#transparent;
  background-image:url(none);
}

/** Page structure tweaks for layout editor wireframe */
body#layout #header { 
  margin-left: 0px;
  margin-right: 0px;
}

.bloggerPmPBar { background-color:#003366;
color:#9cceff;
font-family: Arial, Helvetica, sans-serif;
font-size:10px;
text-align:left;
padding:2px 2px 2px 6px;}
.bloggerPmPBar a {color:#9cceff}
.PmPLogo {float:right;padding-right:9px;}
www.pimp-


]]></b:skin>
  </head>

  <body>


<div class="bloggerPmPBar" style="cursor:pointer;"><div class="PmPLogo"><span style="position:relative;top:-1px;left:0px">�</span> <a href="https://www.pimp-my-profile.com/">Pimp-My-Profile.com</a></div>
    <a href="https://www.pimp-my-profile.com/">BLOGGER TEMPLATES</a> <a href="https://weirdnutdaily.com/">Funny Pictures</a> <span style="position:relative;top:-1px;left:0px;">�</span> </div>

<div id='outer-wrapper'><div id='wrap2'>

    <!-- skip links for text browsers -->
    <span id='skiplinks' style='display:none;'>
      <a href='#main'>skip to main </a> |
      <a href='#sidebar'>skip to sidebar</a>
    </span>

    <div id='header-wrapper'>
      <b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
<b:widget id='Header1' locked='true' title='Layouts (Header)' type='Header'>
<b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == "REPLACE"'>
      <!--Show just the image, no text-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + "_headerimg"' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
      </div>
<center><div style="margin-bottom:5px;background-image:url(https://ct.pimp-my-profile.com/blank.gif);background-position:center center;background-repeat;no-repeat;width:0px !important;height:0px !important;">&#160;</div></center>

    <b:else/>
      <!--Show image as background to text-->
      <div expr:style='"background-image: url("" + data:sourceUrl + ""); "                      + "background-repeat: no-repeat; "                      + "width: " + data:width + "px; "                      + "height: " + data:height + "px;"' id='header-inner'>
        <div class='titlewrapper' style='background: transparent'>
          <h1 class='title' style='background: transparent; border-width: 0px'>
            <b:if cond='data:blog.url == data:blog.homepageUrl'>
              <data:title/>
            <b:else/>
              <a expr:href='data:blog.homepageUrl'><data:title/></a>
            </b:if>
          </h1>
        </div>
        <div class='descriptionwrapper'>
          <p class='description'><span><data:description/></span></p>
        </div>
      </div>

<center><div style="margin-bottom:5px;background-image:url(https://ct.pimp-my-profile.com/blank.gif);background-position:center center;background-repeat;no-repeat;width:0px !important;height:0px !important;">&#160;</div></center>

    </b:if>

  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:if cond='data:blog.url == data:blog.homepageUrl'>
            <data:title/>
          <b:else/>
            <a expr:href='data:blog.homepageUrl'><data:title/></a>
          </b:if>
        </h1>
      </div>
      <div class='descriptionwrapper'>
        <p class='description'><span><data:description/></span></p>
      </div>
    </div>

<center><div style="margin-bottom:5px;background-image:url(https://ct.pimp-my-profile.com/blank.gif);background-position:center center;background-repeat;no-repeat;width:0px !important;height:0px !important;">&#160;</div></center>

  </b:if>

</b:includable>
</b:widget>
</b:section>
    </div>
 
    <div id='content-wrapper'>

      <div id='crosscol-wrapper' style='text-align:center'>
        <b:section class='crosscol' id='crosscol' showaddelement='no'/>
      </div>

      <div id='main-wrapper'>
        <b:section class='main' id='main' showaddelement='no'>
<b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog'>
<b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + "_blog-pager-newer-link"' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + "_blog-pager-older-link"' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:blog.homepageUrl != data:blog.url'>
      <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
      <b:else/>
      <b:if cond='data:newerPageUrl'>
        <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
      </b:if>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
<b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'> 
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + "_backlinks-create-link"' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
<b:includable id='post' var='post'>
  <div class='post uncustomized-post-template'>
    <a expr:name='data:post.id'/>
    <b:if cond='data:post.title'>
      <h3 class='post-title'>
     <b:if cond='data:post.link'>
       <a expr:href='data:post.link'><data:post.title/></a>
     <b:else/>
        <b:if cond='data:post.url'>
          <a expr:href='data:post.url'><data:post.title/></a>
        <b:else/>
          <data:post.title/>
        </b:if>
     </b:if>
      </h3>
    </b:if>

    <div class='post-header-line-1'/>

    <div class='post-body'>
      <p><data:post.body/></p>
      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>
    <div class='post-footer'>
    <p class='post-footer-line post-footer-line-1'>
      <span class='post-author'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/> <data:post.author/>
        </b:if>
      </span>

      <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
        <b:if cond='data:post.url'>
          <a class='timestamp-link' expr:href='data:post.url' title='permanent link'><data:post.timestamp/></a>
        </b:if>
        </b:if>
      </span>

      <span class='post-comment-link'>
        <b:if cond='data:blog.pageType != "item"'>

          <b:if cond='data:post.allowComments'>
            <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
          </b:if>
        </b:if>
      </span>

       <!-- backlinks -->
       <span class='post-backlinks post-comment-link'>
         <b:if cond='data:blog.pageType != "item"'>
           <b:if cond='data:post.showBacklinks'>
             <a class='comment-link' expr:href='data:post.url + "#links"'><data:top.backlinkLabel/></a>
           </b:if>
         </b:if>
       </span>

      <span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
            <span class='email-post-icon'>&#160;</span>
          </a>
          </span>
        </b:if>

        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span>
      </p>

      <p class='post-footer-line post-footer-line-2'>
      <span class='post-labels'>
        <b:if cond='data:post.labels'>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != "true"'>,</b:if>
          </b:loop>
        </b:if>
      </span>
      </p>

      <p class='post-footer-line post-footer-line-3'/>
    </div>
  </div>
</b:includable>
<b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='"item-control " + data:comment.adminClass'>
    <a expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
      <span class='delete-comment-icon'>&#160;</span>
    </a>
  </span>
</b:includable>
<b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
<b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != "item"'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

    <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments'>
          <b:if cond='data:post.feedLinks'>
            <b:include data='post.feedLinks' name='feedLinksBody'/>
          </b:if>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
<b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='"item-control " + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <span class='delete-comment-icon'>&#160;</span>
    </a>
  </span>
</b:includable>
<b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
<b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='"item-control " + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <span class='quick-edit-icon'>&#160;</span>
      </a>
    </span>
  </b:if>
</b:includable>
<b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4>
        <b:if cond='data:post.numComments == 1'>
          1 <data:commentLabel/>:
        <b:else/>
          <data:post.numComments/> <data:commentLabelPlural/>:
        </b:if>
      </h4>

      <dl id='comments-block'>
        <b:loop values='data:post.comments' var='comment'>
          <dt class='comment-author' expr:id='"comment-" + data:comment.id'>
            <a expr:name='"comment-" + data:comment.id'/>
            <b:if cond='data:comment.authorUrl'>
              <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
            <b:else/>
              <data:comment.author/>
            </b:if>
            <data:commentPostedByMsg/>
          </dt>
          <dd class='comment-body'>
            <b:if cond='data:comment.isDeleted'>
              <span class='deleted-comment'><data:comment.body/></span>
            <b:else/>
              <p><data:comment.body/></p>
            </b:if>
          </dd>
          <dd class='comment-footer'>
            <span class='comment-timestamp'>
              <a expr:href='"#comment-" + data:comment.id' title='comment permalink'>
                <data:comment.timestamp/>
              </a>
              <b:include data='comment' name='commentDeleteIcon'/>
            </span>
          </dd>
        </b:loop>
      </dl>

      <p class='comment-footer'>
        <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
      </p>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + "_backlinks-container"'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
<b:includable id='main' var='top'>
  <!-- posts -->
  <div class='blog-posts'>

    <b:include data='top' name='status-message'/>

    <data:adStart/>
    <b:loop values='data:posts' var='post'>
      <b:if cond='data:post.dateHeader'>
        <h2 class='date-header'><data:post.dateHeader/></h2>
      </b:if>
      <b:include data='post' name='post'/>
      <b:if cond='data:blog.pageType == "item"'>
        <b:include data='post' name='comments'/>
      </b:if>
    </b:loop>
    <data:adEnd/>
  </div>

  <!-- navigation -->
  <b:include name='nextprev'/>

  <!-- feed links -->
  <b:include name='feedLinks'/>
</b:includable>
</b:widget>
</b:section>
      </div>

      <div id='sidebar-wrapper'>
        <b:section class='sidebar' id='sidebar' preferred='yes'>
<b:widget id='BlogArchive1' locked='false' title='Blog Archive' type='BlogArchive'>
<b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + "_ArchiveList"'>
    <b:if cond='data:style == "HIERARCHY"'>
     <b:include data='data' name='interval'/>
    </b:if>
    <b:if cond='data:style == "FLAT"'>
      <b:include data='data' name='flat'/>
    </b:if>
    <b:if cond='data:style == "MENU"'>
      <b:include data='data' name='menu'/>
    </b:if>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
<b:includable id='flat' var='data'>
  <ul>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
<b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + "_ArchiveMenu"'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
<b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='i'>
      <ul>
        <li expr:class='"archivedate " + data:i.expclass'>
          <b:include data='i' name='toggle'/>
          <a class='post-count-link' expr:href='data:i.url'><data:i.name/></a>
            (<span class='post-count'><data:i.post-count/></span>)
          <b:if cond='data:i.data'>
            <b:include data='i.data' name='interval'/>
          </b:if>
          <b:if cond='data:i.posts'>
            <b:include data='i.posts' name='posts'/>
          </b:if>
        </li>
      </ul>
  </b:loop>
</b:includable>
<b:includable id='toggle' var='interval'>
  <b:if cond='data:interval.toggleId'>
  <b:if cond='data:interval.expclass == "expanded"'>
    <a class='toggle' expr:href='data:widget.actionUrl + "&amp;action=toggle" +       "&amp;dir=close&amp;toggle=" + data:interval.toggleId +       "&amp;toggleopen=" + data:toggleopen'>
        <span class='zippy toggle-open'>&#9660; </span>
    </a>
  <b:else/>
    <a class='toggle' expr:href='data:widget.actionUrl + "&amp;action=toggle" +         "&amp;dir=open&amp;toggle=" + data:interval.toggleId +         "&amp;toggleopen=" + data:toggleopen'>
          <span class='zippy'>&#9658; </span>
    </a>
  </b:if>
 </b:if>
</b:includable>
<b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='i'>
      <li><a expr:href='data:i.url'><data:i.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
</b:widget>
<b:widget id='Profile1' locked='false' title='About Me' type='Profile'>
<b:includable id='main'>
    <b:if cond='data:title != ""'>
      <h2><data:title/></h2>
    </b:if>
    <div class='widget-content'>
    <b:if cond='data:team == "true"'> <!-- team blog profile -->
      <ul>
        <b:loop values='data:authors' var='i'>
          <li><a expr:href='data:i.userUrl'><data:i.display-name/></a></li>
        </b:loop>
      </ul>

      <b:else/> <!-- normal blog profile -->

      <b:if cond='data:photo.url != ""'>
        <a expr:href='data:userUrl'><img class='profile-img' expr:alt='data:photo.alt' expr:height='data:photo.height' expr:src='data:photo.url' expr:width='data:photo.width'/></a>
      </b:if>

      <dl class='profile-datablock'>
        <dt class='profile-data'><data:displayname/></dt>

        <b:if cond='data:showlocation == "true"'>
          <dd class='profile-data'><data:location/></dd>
        </b:if>

        <b:if cond='data:aboutme != ""'><dd class='profile-textblock'><data:aboutme/></dd></b:if>
      </dl>
      <a class='profile-link' expr:href='data:userUrl'><data:viewProfileMsg/></a>
    </b:if>
<br/>Visitors<br/>
<a href="https://m.maploco.com/detad/983181783"><img style="border:0px;" src="https://www.maploco.com/vmad/983181783" alt="Locations of Site Visitors" title="Locations of Site Visitors"/></a>  

     <b:include name='quickedit'/>
    </div>
  </b:includable>

</b:widget>
</b:section>
      </div>

      <!-- spacer for skins that want sidebar and main to be the same height-->
      <div class='clear'>&#160;</div>

    </div> <!-- end content-wrapper -->

    <div id='footer-wrapper'>
      <b:section class='footer' id='footer'/>
    </div>

  </div></div> <!-- end outer-wrapper -->
</body>
</html>

