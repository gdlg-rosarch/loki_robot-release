^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package loki_robot
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.2 (2017-12-30)
------------------
* Merge branch 'fix-`#1 <https://github.com/UbiquityRobotics/loki_robot/issues/1>`_' of github.com:UbiquityRobotics/loki_robot
* Merge pull request `#3 <https://github.com/UbiquityRobotics/loki_robot/issues/3>`_ from `UbiquityRobotics/fix-#1 <https://github.com/UbiquityRobotics/fix-/issues/1>`_
  Mirror magni_robot in loki_robot
* Contributors: Rohan Agrawal

0.0.1 (2017-12-27)
------------------
* make metapackage pull in all the subpackages
  you need to use exec_depend on all the subpackages in the metapackage
  otherwise the installing the metapackage won't pull in the others
* remove old ur launch stuff, start moving to metapackage
  This is the first step in resolving issue `#1 <https://github.com/UbiquityRobotics/loki_robot/issues/1>`_
* Scrubbed repository down to the README.md .
* Using format 2, added ubiquity_launches dependancy
* added loki_robot meta package
* Contributors: Rohan Agrawal, Wayne C. Gramlich
