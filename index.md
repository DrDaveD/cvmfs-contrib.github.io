## Welcome to cvmfs-contrib

cvmfs-contrib is a place for collecting software packages related to
the [CernVM Filesystem](https://cernvm.cern.ch/portal/filesystem)
(CVMFS) that are contributed by the community and not supported by the
CVMFS development team.  It is hosted both on a
[github organization](https://github.com/cvmfs-contrib) and on an
[OpenSUSE Build Service (OBS) project](https://build.opensuse.org/project/show/home:cvmfs).
The packages are built into the OBS project's yum repositories for
Redhat Enterprise Linux and derivatives, and in some cases packages
are also built into its apt repositories for Debian and Ubuntu.

If you have any issues with a particular package, please submit a github
issue for that package.  If you would like to request adding a new
package or have a question about the cvmfs-contrib project as a whole,
please send it to [cvmfs-talk@cern.ch](mailto:cvmfs-talk@cern.ch).
Membership in that mailing list is managed through the 
[CERN groups manager](https://groups.cern.ch/Pages/GroupSearch.aspx?k=cvmfs-talk).

### Enabling installing from cvmfs-contrib yum repositories

In order to enable installing from the cvmfs-contrib yum repository
run the following command:

```
sudo yum install -y https://ecsft.cern.ch/dist/cvmfs/cvmfs-contrib-release/cvmfs-contrib-release-latest.noarch.rpm
```

### Enabling installing from cvmfs-contrib apt repositories

In order to enable installing from the cvmfs-contrib apt repository
run the following commands:

```
wget https://ecsft.cern.ch/dist/cvmfs/cvmfs-contrib-release/cvmfs-contrib-release-latest_all.deb
sudo dpkg -i cvmfs-contrib-release-latest_all.deb
rm -f cvmfs-contrib-release-latest_all.deb
sudo apt-get update
```
