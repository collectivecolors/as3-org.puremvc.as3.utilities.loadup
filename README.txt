PureMVC (Standard) Loadup utility releases for use as Git submodules in 
ActionScript or Flex applications.

****************************
* IMPORTING AS A SUBMODULE *
****************************

The following instructions assume that you have a git repository set up on your
application directory.

To import this package into your application, run :

----------
 Commands 
 
$  git submodule add git@github.com:collectivecolors/as3-org.puremvc.as3.git
                     {BASE_DIR}/org/puremvc/as3
                     
$  git submodule add git@github.com:collectivecolors/as3-org.puremvc.as3.utilities.loadup.git
                     {BASE_DIR}/org/puremvc/as3/utilities/loadup
                     
$  git submodule init

----------

Where :

 {BASE_DIR} is your root source folder.  
    
    If your repository is at the root source path then just use the package
    names, org/puremvc/as3 and org/puremvc/as3/utilities/loadup

*********
* NOTES * 
*********

1. We did not create and are not the maintainers of the PureMVC loadup utility.
   Thanks to Philip Sexton at http://trac.puremvc.org/PureMVC/wiki/ProjectOwners/PhilipSexton 
   for this very handy utility! 
   
2. Please see http://trac.puremvc.org/Utility_AS3_Loadup for more information 
   about the PureMVC loadup utility.

3. The official svn repository from which this git repo is based upon is 
   http://svn.puremvc.org/Utility_AS3_Loadup.
   
4. We will try to update this repository as close to actual svn release as 
   possible.  If you notice that this repo is stale then send us a message 
   and we'll update it.