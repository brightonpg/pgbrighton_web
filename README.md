# pgbrighton_web
www.pgbrighton.uk's public content repository 

The website is generated using the stating html generator [Hugo IO](https://gohugo.io/).

In order to contribute to the website you should first install hugoio. 
Hugo supports any major operating system. 

The install instructions are [available here](https://gohugo.io/getting-started/installing/)

After the binary is installed you should fork this repository and clone it on your computer.

As www.pgbrighton.uk is using the [theme mainroad](https://themes.gohugo.io/mainroad/) you should clone the theme's git in the **subfolder web/themes/mainroad**.

    e.g.
    cd git/pgbrighton_web/web/
    mkdir themes
    cd themes
    git clone https://github.com/Vimux/Mainroad.git mainroad
    
To run the website local step into the web directory and run the hugo server
    
    e.g.
    cd git/pgbrighton_web/web/
    hugo -D server --disableFastRender
    
Open a browser and navigate to [http://localhost:1313](http://localhost:1313)

For adding new content please refer to the hugo io documentation.

When you are happy with the new page create a new PR to have your page merged.

