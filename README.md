dxa-web-application-dotnet
===
SDL Digital Experience Accelerator .NET MVC web application


About
-----
The SDL Digital Experience Accelerator (formerly known as the SDL Tridion Reference Implementation) is a reference implementation of SDL Tridion intended to help you create, design and publish an SDL Tridion-based Web site quickly.

You can find more details and a download of the entire release on https://community.sdl.com/developers/tridion_developer/m/mediagallery/852


Support
---------------
The SDL Digital Experience Accelerator is intended as a toolkit to help the SDL Tridion community and is not an officially supported SDL Tridion product.

If you encounter problems, reach out to the community: http://tridion.stackexchange.com/


Sources
-------

The official v1.1 release (downloadable on https://community.sdl.com/developers/tridion_developer/m/mediagallery/852) contains only the **Site** project in the web-application Visual Studio solution, since only that part of the source is considered public API (as in, you are expected to change that). This repository contains the full source of all the `Sdl.Web.*` DLLs to give you insight in how the solution is built and what is there available for you to extend. You are free to use these sources under the terms and conditions of the license mentioned below, however we suggest you only change the code of the **Site** project and make use of the compiled `Sdl.Web.Common.dll`, `Sdl.Web.Mvc.dll` and `Sdl.Web.Tridion.dll` from the SDL Community site. 


Documentation
-------------

Documentation can be found online in the SDL doc portal, you can find details about this in the download on the SDL Community site.


Repositories
------------

The following repositories with source code are available:

 - https://github.com/sdl/dxa-content-management - Core Template Building Blocks
 - https://github.com/sdl/dxa-html-design - Whitelabel HTML Design
 - https://github.com/sdl/dxa-modules - Modules
 - https://github.com/sdl/dxa-web-application-dotnet - .NET MVC web application
 - https://github.com/sdl/dxa-web-application-java - Java Spring MVC web application


Branching model
---------------

We intend to follow Gitflow (http://nvie.com/posts/a-successful-git-branching-model/) with the following main branches:

 - master - Stable 
 - develop - Unstable
 - release/x.y - Release version x.y

Please submit your pull requests on develop. In the near future we intend to push our changes to develop and master from our internal repositories, so you can follow our development process.


License
-------
Copyright (c) 2014-2015 SDL Group.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

	http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.
