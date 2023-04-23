# Getting Started with Webhosting
 
## Starting the journey
It's a little bit daunting if you're not a web developer and you're suddenly tasked with getting a webpage out there that people can browse to. On top of this I knew that my eventual plan was for my website to be capable of serving a mixture of content.

I decided I wanted to utiilise MarkDown for the more blog style pages - aside from being a RichText editor, it supports a few different features I need (Namely Latex and iFrames) as well as meaning I wasn't tied in to any particular CMS system (Such as wordpress) which I values as I knew I would probably make at least a couple of mistakes when deciding on the hosting stack, and being able to just point at an MD file that I am iterating on in Git would be an easier task.

I realised that Wordpress has a few plugins to render Markdown, but came across Grav https://learn.getgrav.org/ during my google journey which I hadn't heard of before.

It purports to be a stripped down CMS system, authored through MarkDown, but (in its own words) 

> "There are many powerful open source CMS solutions for building complex websites. Some of the more commonly used ones are Joomla, WordPress, and Drupal. The downside of these platforms is that they have a steep learning curve associated with them. This requires a significant amount of your time - and this may be the time that you do not have."

Which appealed to me, so I decided to do my website V1 using Grav.

The other requirements I have are to be able to serve Unity WebGL projects which exist on an AWS S3 bucket. And embed them into the Markdown documents via \<iFrames\> so that I am able to render a Uniy project in the middle of a blog post.

However Unity rendering is stage 2. So first I just want to get a Markdown page rendered on a local server.

### Step 1 - Getting a local server up and running with Grav

Grav actually comes with a built in PHP server (https://learn.getgrav.org/16/webservers-hosting/servers/grav-built-in) so I started focussing my attention here.



<div>
  <iframe id="inlineFrameExample"
      title="Inline Frame Example"
      width="300"
      height="200"
      src="https://commons.wikimedia.org/wiki/File:HelloWorld.svg">
  </iframe>
</div>