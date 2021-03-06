# lifecycle-demo

[![Build Status](https://travis-ci.org/atomisthq/lifecycle-demo.svg?branch=master)](https://travis-ci.org/atomisthq/lifecycle-demo)



This [Rug][rug] archive contains My new project 

[rug]: http://docs.atomist.com/
  
After you create a project with this generator, you may enjoy the compatible editors   in [atomisthqa:rug-editors](https://github.com/atomisth-rugs/rug-edito   rs).        
  s dd  
## Rugs   ss vbla sfsf             ### AddReadme   xxx   sfadad  
sd   adad
The AddReadme editor adds a GitHub-like `README.mdadad` to a projxxxect. 
  
#### Prerequisites      
     
Before running this editor, you must have the following prerequisites ccccccc
satisfied.  sca

*   A source code repository 
#### Parameters   s

To run this editor, you must supply the following parameters.

Name | Required | Default | Description
-----|----------|---------|------------
`project_name` | Yes | | A valid GitHub repository name.
`description` | No | My new project | A brief des   cription of the project between 1 and 100 characters.
sfsf
[semver]: http://semver.org  
  
#### Running ssadad

Run it as follows:adad
  
```
$ cd to/the/repo
$ rug edit atomisthq:lifecycle-demo:AddReadme \
    project_name=fun-project \
    description='A project that needs a README'
```

This will create a simple `README.md` file in the top-level directory
of the source code repository.  If you are happy with the change,
commit the changes.

## Support


General support questions should be discussed in the `#support`
channel on our community Slack team
at [atomist-community.slack.com][slack]. 

If you find a problem, please create an [issue][].fdffgdg

[issue]: https://github.com/atomisthq/lifecycle-demo/issues

## Development

You can build, test, and install the project locally with
the [Rug CLI][cli].

[cli]: https://github.com/atomist/rug-cli

```
$ rug test
$ rug install
```

To create a new release of the project, simply push a tag of the form
`M.N.P` where `M`, `N`, and `P` are integers that form the next
appropriate [semantic version][semver] for release.  For example:

[semver]: http://semver.org

```
$ git tag -a 1.2.3
```

The Travis CI build (see badge at the top of this page) will
automatically create a GitHub release using the tag name for the
release and the comment provided on the annotated tag as the contents
of the release notes.  It will also automatically upload the needed
artifacts.
 

---
Created by [Atomist][atomis t].
Need Help?  [Join  our Slack team][slack].

[atomist]: https://www.atomist.com/
[slack]: https://join.atomist.com/
