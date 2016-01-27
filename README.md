# Admin Authorization plugin for using Prose.io hosted on BowTie.io

'Admin-Install' is a Jeykll component that simplifies the process of authenticating an admin user of a  [BowTie.io](https://bowtie.io) project repository. This plugin is designed for use in conjunction with  the [Prose](http://prose.io) editor.

This template is meant as a learning resource. It is compatible with other BowTie components and templates, and the BowTie test environment.

The theme uses [jquery](https://jquery.com/), [bootstrap](http://getbootstrap.com/), [fontawesome](https://fortawesome.github.io/Font-Awesome/), and a custom theme styles written in [SCSS](http://sass-lang.com/).  

### [View Example Site](https://adminsetup.bowtied.io/)


## Documentation
This component includes an index.html page and javascript to help a user obtain Admin access for a BowTie repository. Prose should be installed at `/admin/` in the project repository, and configured for use with BowTie. The process included in this demo relies on user registration and policy controls provided by BowTie.

This component is compatible with Jekyll 3.x. Jekyll will interpret liquid, markdown, and  standard HTML. For information on using Jekyll see the [Jekyll documentation](http://jekyllrb.com/). For thorough documentation of this template and the added BowTie features, view the [BowTie docs](https://bowtie.io/docs/#projects).

## Usage

Copy the content of this repo to a directory outside of the /admin/ directory of your repository and push the files to your remote branch. In the published example, the directory containing these files is `/admin-install/`.

BowTie builds Jekyll when content is pushed to your repository.

Place a link to `/admin-install/` on your site so that users can access the page for authentication.

_NOTE: For instructions on install the Prose editor, see this resource [Installing Prose on Bowtie](https://bowtie.io/help/installing-prose-on-bowtie/)._
