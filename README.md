
# DataEngineer_handson

ubuntu:~/environment $ df -kh
ubuntu:~/environment $ df -kh
Filesystem      Size  Used Avail Use% Mounted on
udev            1.9G     0  1.9G   0% /dev
tmpfs           388M  784K  387M   1% /run
/dev/nvme0n1p1   31G  8.2G   23G  27% /
tmpfs           1.9G     0  1.9G   0% /dev/shm
tmpfs           5.0M     0  5.0M   0% /run/lock
tmpfs           1.9G     0  1.9G   0% /sys/fs/cgroup
/dev/loop0       56M   56M     0 100% /snap/core18/2128
/dev/loop1      100M  100M     0 100% /snap/core/11606
/dev/loop2       25M   25M     0 100% /snap/amazon-ssm-agent/4046
/dev/loop3       33M   33M     0 100% /snap/snapd/12883
tmpfs           388M   p
ubuntu:~/environment $ python3
Python 3.6.9 (default, Jan 26 2021, 15:33:00) 
[GCC 8.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
ubuntu:~/environment $ ls -lart
total 16
-rw-r--r--  1 ubuntu ubuntu  569 Sep 14 03:48 README.md
drwxr-xr-x  3 ubuntu ubuntu 4096 Sep 19 19:31 .
drwxrwxr-x  3 ubuntu ubuntu 4096 Sep 19 19:31 .c9
drwxr-xr-x 13 ubuntu ubuntu 4096 Sep 19 20:10 ..
ubuntu:~/environment $ mkdir delab
ubuntu:~/environment $ cd delab/
ubuntu:~/environment/delab $ python3 -m venv delab-venv
ubuntu:~/environment/delab $ find delab-venv/
delab-venv/
delab-venv/lib
delab-venv/lib/python3.6
delab-venv/lib/python3.6/site-packages
delab-venv/lib/python3.6/site-packages/easy_install.py
delab-venv/lib/python3.6/site-packages/pip
delab-venv/lib/python3.6/site-packages/pip/__main__.py
delab-venv/lib/python3.6/site-packages/pip/_vendor
delab-venv/lib/python3.6/site-packages/pip/_vendor/__pycache__
delab-venv/lib/python3.6/site-packages/pip/_vendor/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/_vendor/__init__.py
delab-venv/lib/python3.6/site-packages/pip/index.py
delab-venv/lib/python3.6/site-packages/pip/status_codes.py
delab-venv/lib/python3.6/site-packages/pip/basecommand.py
delab-venv/lib/python3.6/site-packages/pip/vcs
delab-venv/lib/python3.6/site-packages/pip/vcs/mercurial.py
delab-venv/lib/python3.6/site-packages/pip/vcs/bazaar.py
delab-venv/lib/python3.6/site-packages/pip/vcs/__pycache__
delab-venv/lib/python3.6/site-packages/pip/vcs/__pycache__/mercurial.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/vcs/__pycache__/subversion.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/vcs/__pycache__/git.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/vcs/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/vcs/__pycache__/bazaar.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/vcs/git.py
delab-venv/lib/python3.6/site-packages/pip/vcs/subversion.py
delab-venv/lib/python3.6/site-packages/pip/vcs/__init__.py
delab-venv/lib/python3.6/site-packages/pip/wheel.py
delab-venv/lib/python3.6/site-packages/pip/pep425tags.py
delab-venv/lib/python3.6/site-packages/pip/req
delab-venv/lib/python3.6/site-packages/pip/req/req_uninstall.py
delab-venv/lib/python3.6/site-packages/pip/req/req_file.py
delab-venv/lib/python3.6/site-packages/pip/req/req_set.py
delab-venv/lib/python3.6/site-packages/pip/req/__pycache__
delab-venv/lib/python3.6/site-packages/pip/req/__pycache__/req_set.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/req/__pycache__/req_file.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/req/__pycache__/req_uninstall.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/req/__pycache__/req_install.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/req/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/req/req_install.py
delab-venv/lib/python3.6/site-packages/pip/req/__init__.py
delab-venv/lib/python3.6/site-packages/pip/utils
delab-venv/lib/python3.6/site-packages/pip/utils/appdirs.py
delab-venv/lib/python3.6/site-packages/pip/utils/filesystem.py
delab-venv/lib/python3.6/site-packages/pip/utils/logging.py
delab-venv/lib/python3.6/site-packages/pip/utils/encoding.py
delab-venv/lib/python3.6/site-packages/pip/utils/build.py
delab-venv/lib/python3.6/site-packages/pip/utils/setuptools_build.py
delab-venv/lib/python3.6/site-packages/pip/utils/outdated.py
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/setuptools_build.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/encoding.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/filesystem.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/ui.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/deprecation.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/hashes.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/appdirs.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/outdated.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/glibc.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/packaging.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/build.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/__pycache__/logging.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/utils/glibc.py
delab-venv/lib/python3.6/site-packages/pip/utils/ui.py
delab-venv/lib/python3.6/site-packages/pip/utils/hashes.py
delab-venv/lib/python3.6/site-packages/pip/utils/packaging.py
delab-venv/lib/python3.6/site-packages/pip/utils/__init__.py
delab-venv/lib/python3.6/site-packages/pip/utils/deprecation.py
delab-venv/lib/python3.6/site-packages/pip/commands
delab-venv/lib/python3.6/site-packages/pip/commands/uninstall.py
delab-venv/lib/python3.6/site-packages/pip/commands/freeze.py
delab-venv/lib/python3.6/site-packages/pip/commands/wheel.py
delab-venv/lib/python3.6/site-packages/pip/commands/list.py
delab-venv/lib/python3.6/site-packages/pip/commands/completion.py
delab-venv/lib/python3.6/site-packages/pip/commands/show.py
delab-venv/lib/python3.6/site-packages/pip/commands/hash.py
delab-venv/lib/python3.6/site-packages/pip/commands/help.py
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/completion.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/wheel.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/show.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/download.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/check.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/list.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/help.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/hash.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/install.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/search.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/uninstall.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/__pycache__/freeze.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/commands/download.py
delab-venv/lib/python3.6/site-packages/pip/commands/search.py
delab-venv/lib/python3.6/site-packages/pip/commands/__init__.py
delab-venv/lib/python3.6/site-packages/pip/commands/install.py
delab-venv/lib/python3.6/site-packages/pip/commands/check.py
delab-venv/lib/python3.6/site-packages/pip/compat
delab-venv/lib/python3.6/site-packages/pip/compat/dictconfig.py
delab-venv/lib/python3.6/site-packages/pip/compat/__pycache__
delab-venv/lib/python3.6/site-packages/pip/compat/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/compat/__pycache__/dictconfig.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/compat/__init__.py
delab-venv/lib/python3.6/site-packages/pip/__pycache__
delab-venv/lib/python3.6/site-packages/pip/__pycache__/wheel.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/download.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/status_codes.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/locations.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/pep425tags.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/baseparser.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/basecommand.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/exceptions.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/index.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/__main__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/__pycache__/cmdoptions.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/locations.py
delab-venv/lib/python3.6/site-packages/pip/download.py
delab-venv/lib/python3.6/site-packages/pip/baseparser.py
delab-venv/lib/python3.6/site-packages/pip/models
delab-venv/lib/python3.6/site-packages/pip/models/index.py
delab-venv/lib/python3.6/site-packages/pip/models/__pycache__
delab-venv/lib/python3.6/site-packages/pip/models/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/models/__pycache__/index.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/models/__init__.py
delab-venv/lib/python3.6/site-packages/pip/cmdoptions.py
delab-venv/lib/python3.6/site-packages/pip/exceptions.py
delab-venv/lib/python3.6/site-packages/pip/operations
delab-venv/lib/python3.6/site-packages/pip/operations/freeze.py
delab-venv/lib/python3.6/site-packages/pip/operations/__pycache__
delab-venv/lib/python3.6/site-packages/pip/operations/__pycache__/check.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/operations/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/operations/__pycache__/freeze.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip/operations/__init__.py
delab-venv/lib/python3.6/site-packages/pip/operations/check.py
delab-venv/lib/python3.6/site-packages/pip/__init__.py
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/WHEEL
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/zip-safe
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/INSTALLER
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/entry_points.txt
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/DESCRIPTION.rst
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/top_level.txt
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/METADATA
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/RECORD
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/dependency_links.txt
delab-venv/lib/python3.6/site-packages/setuptools-39.0.1.dist-info/metadata.json
delab-venv/lib/python3.6/site-packages/pkg_resources
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/appdirs.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/six.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/pyparsing.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/__pycache__
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/__pycache__/pyparsing.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/__pycache__/appdirs.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/__pycache__/six.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/requirements.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/utils.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__about__.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/markers.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/_compat.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/__about__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/version.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/_structures.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/_compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/utils.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/specifiers.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/markers.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__pycache__/requirements.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/version.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/_structures.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/specifiers.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/packaging/__init__.py
delab-venv/lib/python3.6/site-packages/pkg_resources/_vendor/__init__.py
delab-venv/lib/python3.6/site-packages/pkg_resources/extern
delab-venv/lib/python3.6/site-packages/pkg_resources/extern/__pycache__
delab-venv/lib/python3.6/site-packages/pkg_resources/extern/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/extern/__init__.py
delab-venv/lib/python3.6/site-packages/pkg_resources/__pycache__
delab-venv/lib/python3.6/site-packages/pkg_resources/__pycache__/py31compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pkg_resources/py31compat.py
delab-venv/lib/python3.6/site-packages/pkg_resources/__init__.py
delab-venv/lib/python3.6/site-packages/pkg_resources-0.0.0.dist-info
delab-venv/lib/python3.6/site-packages/pkg_resources-0.0.0.dist-info/WHEEL
delab-venv/lib/python3.6/site-packages/pkg_resources-0.0.0.dist-info/INSTALLER
delab-venv/lib/python3.6/site-packages/pkg_resources-0.0.0.dist-info/DESCRIPTION.rst
delab-venv/lib/python3.6/site-packages/pkg_resources-0.0.0.dist-info/METADATA
delab-venv/lib/python3.6/site-packages/pkg_resources-0.0.0.dist-info/RECORD
delab-venv/lib/python3.6/site-packages/pkg_resources-0.0.0.dist-info/metadata.json
delab-venv/lib/python3.6/site-packages/__pycache__
delab-venv/lib/python3.6/site-packages/__pycache__/easy_install.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/WHEEL
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/INSTALLER
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/entry_points.txt
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/DESCRIPTION.rst
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/top_level.txt
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/METADATA
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/RECORD
delab-venv/lib/python3.6/site-packages/pip-9.0.1.dist-info/metadata.json
delab-venv/lib/python3.6/site-packages/setuptools
delab-venv/lib/python3.6/site-packages/setuptools/_vendor
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/six.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/pyparsing.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/__pycache__
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/__pycache__/pyparsing.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/__pycache__/six.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/requirements.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/utils.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__about__.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/markers.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/_compat.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/__about__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/version.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/_structures.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/_compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/utils.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/specifiers.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/markers.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__pycache__/requirements.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/version.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/_structures.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/specifiers.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/packaging/__init__.py
delab-venv/lib/python3.6/site-packages/setuptools/_vendor/__init__.py
delab-venv/lib/python3.6/site-packages/setuptools/extension.py
delab-venv/lib/python3.6/site-packages/setuptools/cli-32.exe
delab-venv/lib/python3.6/site-packages/setuptools/namespaces.py
delab-venv/lib/python3.6/site-packages/setuptools/unicode_utils.py
delab-venv/lib/python3.6/site-packages/setuptools/dist.py
delab-venv/lib/python3.6/site-packages/setuptools/py27compat.py
delab-venv/lib/python3.6/site-packages/setuptools/msvc.py
delab-venv/lib/python3.6/site-packages/setuptools/cli-64.exe
delab-venv/lib/python3.6/site-packages/setuptools/package_index.py
delab-venv/lib/python3.6/site-packages/setuptools/config.py
delab-venv/lib/python3.6/site-packages/setuptools/wheel.py
delab-venv/lib/python3.6/site-packages/setuptools/ssl_support.py
delab-venv/lib/python3.6/site-packages/setuptools/monkey.py
delab-venv/lib/python3.6/site-packages/setuptools/pep425tags.py
delab-venv/lib/python3.6/site-packages/setuptools/py33compat.py
delab-venv/lib/python3.6/site-packages/setuptools/depends.py
delab-venv/lib/python3.6/site-packages/setuptools/gui.exe
delab-venv/lib/python3.6/site-packages/setuptools/gui-32.exe
delab-venv/lib/python3.6/site-packages/setuptools/archive_util.py
delab-venv/lib/python3.6/site-packages/setuptools/extern
delab-venv/lib/python3.6/site-packages/setuptools/extern/__pycache__
delab-venv/lib/python3.6/site-packages/setuptools/extern/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/extern/__init__.py
delab-venv/lib/python3.6/site-packages/setuptools/gui-64.exe
delab-venv/lib/python3.6/site-packages/setuptools/site-patch.py
delab-venv/lib/python3.6/site-packages/setuptools/glob.py
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/ssl_support.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/unicode_utils.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/wheel.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/dep_util.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/windows_support.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/launch.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/monkey.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/msvc.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/extension.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/py31compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/namespaces.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/version.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/pep425tags.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/glibc.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/dist.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/lib2to3_ex.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/depends.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/py33compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/archive_util.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/site-patch.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/package_index.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/py27compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/build_meta.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/config.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/py36compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/glob.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/__pycache__/sandbox.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/glibc.py
delab-venv/lib/python3.6/site-packages/setuptools/sandbox.py
delab-venv/lib/python3.6/site-packages/setuptools/version.py
delab-venv/lib/python3.6/site-packages/setuptools/launch.py
delab-venv/lib/python3.6/site-packages/setuptools/dep_util.py
delab-venv/lib/python3.6/site-packages/setuptools/py31compat.py
delab-venv/lib/python3.6/site-packages/setuptools/script.tmpl
delab-venv/lib/python3.6/site-packages/setuptools/script (dev).tmpl
delab-venv/lib/python3.6/site-packages/setuptools/py36compat.py
delab-venv/lib/python3.6/site-packages/setuptools/command
delab-venv/lib/python3.6/site-packages/setuptools/command/sdist.py
delab-venv/lib/python3.6/site-packages/setuptools/command/easy_install.py
delab-venv/lib/python3.6/site-packages/setuptools/command/install_lib.py
delab-venv/lib/python3.6/site-packages/setuptools/command/bdist_egg.py
delab-venv/lib/python3.6/site-packages/setuptools/command/bdist_wininst.py
delab-venv/lib/python3.6/site-packages/setuptools/command/dist_info.py
delab-venv/lib/python3.6/site-packages/setuptools/command/build_clib.py
delab-venv/lib/python3.6/site-packages/setuptools/command/build_ext.py
delab-venv/lib/python3.6/site-packages/setuptools/command/install_scripts.py
delab-venv/lib/python3.6/site-packages/setuptools/command/register.py
delab-venv/lib/python3.6/site-packages/setuptools/command/saveopts.py
delab-venv/lib/python3.6/site-packages/setuptools/command/rotate.py
delab-venv/lib/python3.6/site-packages/setuptools/command/bdist_rpm.py
delab-venv/lib/python3.6/site-packages/setuptools/command/build_py.py
delab-venv/lib/python3.6/site-packages/setuptools/command/upload_docs.py
delab-venv/lib/python3.6/site-packages/setuptools/command/test.py
delab-venv/lib/python3.6/site-packages/setuptools/command/egg_info.py
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/develop.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/install_scripts.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/build_py.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/bdist_wininst.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/install_egg_info.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/saveopts.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/sdist.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/egg_info.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/dist_info.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/upload_docs.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/test.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/__init__.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/install.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/install_lib.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/bdist_rpm.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/rotate.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/bdist_egg.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/easy_install.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/alias.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/register.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/build_ext.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/py36compat.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/upload.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/setopt.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/__pycache__/build_clib.cpython-36.pyc
delab-venv/lib/python3.6/site-packages/setuptools/command/setopt.py
delab-venv/lib/python3.6/site-packages/setuptools/command/alias.py
delab-venv/lib/python3.6/site-packages/setuptools/command/py36compat.py
delab-venv/lib/python3.6/site-packages/setuptools/command/launcher manifest.xml
delab-venv/lib/python3.6/site-packages/setuptools/command/develop.py
delab-venv/lib/python3.6/site-packages/setuptools/command/__init__.py
delab-venv/lib/python3.6/site-packages/setuptools/command/install.py
delab-venv/lib/python3.6/site-packages/setuptools/command/upload.py
delab-venv/lib/python3.6/site-packages/setuptools/command/install_egg_info.py
delab-venv/lib/python3.6/site-packages/setuptools/cli.exe
delab-venv/lib/python3.6/site-packages/setuptools/windows_support.py
delab-venv/lib/python3.6/site-packages/setuptools/__init__.py
delab-venv/lib/python3.6/site-packages/setuptools/lib2to3_ex.py
delab-venv/lib/python3.6/site-packages/setuptools/build_meta.py
delab-venv/include
delab-venv/bin
delab-venv/bin/python3
delab-venv/bin/pip
delab-venv/bin/activate.csh
delab-venv/bin/easy_install
delab-venv/bin/activate.fish
delab-venv/bin/activate
delab-venv/bin/easy_install-3.6
delab-venv/bin/pip3.6
delab-venv/bin/python
delab-venv/bin/pip3
delab-venv/lib64
delab-venv/pyvenv.cfg
delab-venv/share
delab-venv/share/python-wheels
delab-venv/share/python-wheels/six-1.11.0-py2.py3-none-any.whl
delab-venv/share/python-wheels/html5lib-0.999999999-py2.py3-none-any.whl
delab-venv/share/python-wheels/setuptools-39.0.1-py2.py3-none-any.whl
delab-venv/share/python-wheels/urllib3-1.22-py2.py3-none-any.whl
delab-venv/share/python-wheels/pkg_resources-0.0.0-py2.py3-none-any.whl
delab-venv/share/python-wheels/webencodings-0.5-py2.py3-none-any.whl
delab-venv/share/python-wheels/wheel-0.30.0-py2.py3-none-any.whl
delab-venv/share/python-wheels/idna-2.6-py2.py3-none-any.whl
delab-venv/share/python-wheels/distlib-0.2.6-py2.py3-none-any.whl
delab-venv/share/python-wheels/retrying-1.3.3-py2.py3-none-any.whl
delab-venv/share/python-wheels/colorama-0.3.7-py2.py3-none-any.whl
delab-venv/share/python-wheels/pip-9.0.1-py2.py3-none-any.whl
delab-venv/share/python-wheels/certifi-2018.1.18-py2.py3-none-any.whl
delab-venv/share/python-wheels/chardet-3.0.4-py2.py3-none-any.whl
delab-venv/share/python-wheels/distro-1.0.1-py2.py3-none-any.whl
delab-venv/share/python-wheels/packaging-17.1-py2.py3-none-any.whl
delab-venv/share/python-wheels/pyparsing-2.2.0-py2.py3-none-any.whl
delab-venv/share/python-wheels/CacheControl-0.11.7-py2.py3-none-any.whl
delab-venv/share/python-wheels/appdirs-1.4.3-py2.py3-none-any.whl
delab-venv/share/python-wheels/progress-1.2-py2.py3-none-any.whl
delab-venv/share/python-wheels/lockfile-0.12.2-py2.py3-none-any.whl
delab-venv/share/python-wheels/ipaddress-0.0.0-py2.py3-none-any.whl
delab-venv/share/python-wheels/requests-2.18.4-py2.py3-none-any.whl
ubuntu:~/environment/delab $ ls -lart delab-venv/bin/
total 40
lrwxrwxrwx 1 ubuntu ubuntu   16 Sep 19 20:11 python3 -> /usr/bin/python3
lrwxrwxrwx 1 ubuntu ubuntu    7 Sep 19 20:11 python -> python3
drwxrwxr-x 6 ubuntu ubuntu 4096 Sep 19 20:11 ..
-rwxrwxr-x 1 ubuntu ubuntu  271 Sep 19 20:11 easy_install-3.6
-rwxrwxr-x 1 ubuntu ubuntu  271 Sep 19 20:11 easy_install
-rwxrwxr-x 1 ubuntu ubuntu  243 Sep 19 20:11 pip3.6
-rwxrwxr-x 1 ubuntu ubuntu  243 Sep 19 20:11 pip3
-rwxrwxr-x 1 ubuntu ubuntu  243 Sep 19 20:11 pip
-rw-r--r-- 1 ubuntu ubuntu 2449 Sep 19 20:11 activate.fish
-rw-r--r-- 1 ubuntu ubuntu 1285 Sep 19 20:11 activate.csh
-rw-r--r-- 1 ubuntu ubuntu 2229 Sep 19 20:11 activate
drwxrwxr-x 2 ubuntu ubuntu 4096 Sep 19 20:11 .
ubuntu:~/environment/delab $ cd delab-venv/bin/
ubuntu:~/environment/delab/delab-venv/bin $ cd ..
ubuntu:~/environment/delab/delab-venv $ cd ..
ubuntu:~/environment/delab $ source delab-venv/bin/activate
(delab-venv) ubuntu:~/environment/delab $ pip install jupyter
(delab-venv) ubuntu:~/environment/delab $ jupyter lab --ip 0.0.0.0
[I 2021-09-20 07:11:43.427 ServerApp] jupyterlab | extension was successfully linked.
[I 2021-09-20 07:11:43.435 ServerApp] Writing Jupyter server cookie secret to /home/ubuntu/.local/share/jupyter/runtime/jupyter_cookie_secret
[I 2021-09-20 07:11:43.864 ServerApp] nbclassic | extension was successfully linked.
[I 2021-09-20 07:11:43.897 ServerApp] nbclassic | extension was successfully loaded.
[I 2021-09-20 07:11:43.898 LabApp] JupyterLab extension loaded from /home/ubuntu/environment/delab/delab-venv/lib/python3.6/site-packages/jupyterlab
[I 2021-09-20 07:11:43.898 LabApp] JupyterLab application directory is /home/ubuntu/environment/delab/delab-venv/share/jupyter/lab
[I 2021-09-20 07:11:43.901 ServerApp] jupyterlab | extension was successfully loaded.
[I 2021-09-20 07:11:43.902 ServerApp] Serving notebooks from local directory: /home/ubuntu/environment/delab
[I 2021-09-20 07:11:43.902 ServerApp] Jupyter Server 1.11.0 is running at:
[I 2021-09-20 07:11:43.902 ServerApp] http://ip-172-31-25-111:8888/lab?token=abf9656f6fb1bf7655c015998f499684b67f74de87d47ff4
[I 2021-09-20 07:11:43.902 ServerApp]  or http://127.0.0.1:8888/lab?token=abf9656f6fb1bf7655c015998f499684b67f74de87d47ff4
[I 2021-09-20 07:11:43.902 ServerApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[W 2021-09-20 07:11:43.906 ServerApp] No web browser found: could not locate runnable browser.
[C 2021-09-20 07:11:43.906 ServerApp] 
    
    To access the server, open this file in a browser:
        file:///home/ubuntu/.local/share/jupyter/runtime/jpserver-4561-open.html
    Or copy and paste one of these URLs:
        http://ip-172-31-25-111:8888/lab?token=abf9656f6fb1bf7655c015998f499684b67f74de87d47ff4
     or http://127.0.0.1:8888/lab?token=abf9656f6fb1bf7655c015998f499684b67f74de87d47ff4
