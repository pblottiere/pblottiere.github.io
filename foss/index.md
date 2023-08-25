---
layout: left
---

# QGIS ecosystem

## Role

Core committer, French Voting Member and System Administrator, I'm deeply
involved in the <a href="https://www.qgis.org/en/site">QGIS</a> project. To
fulfill these activities, I'm an active contributor of a local user group as
well as a member of the
<a href="https://www.qcooperative.net/">QCooperative</a>, an international group
of opensource GIS experts.

In practice, I participated in the following GitHub repositories:

  + {:.item} <a href="https://github.com/qgis/QGIS">QGIS</a>: qgz format, auxiliary storage, QGIS Server, ...
  + {:.item} <a href="https://github.com/qgis/QGIS-Server-CertifSuite">QGIS-Server-CertifSuite</a>: docker infrastructure to generate WMS 1.3.0, WFS 1.1.0 and OGC API Features OGC certification reports
  + {:.item} <a href="https://github.com/qgis/QGIS-Server-PerfSuite">QGIS-Server-PerfSuite</a>: docker infrastructure to monitor performances and generate statistics reports
  + {:.item} <a href="https://github.com/qgis/QGIS-Sysadmin">QGIS-Sysadmin</a>: automated deployment scripts for qgis4 server
  + {:.item} <a href="https://github.com/qgis/QGIS-Documentation">QGIS-Documentation</a>: documentation repository

## pyogctest

<a href="https://github.com/pblottiere/pyogctest">pyogctest</a> is a Python
tool to run OGC test suites from your terminal. It's currently used and
deployed in the QGIS continuous integration process to test QGIS Server
services and certification status.

## Graffiti

For the purpose of QGIS Server and performance analysis for WMS service, I developped
<a href="https://github.com/pblottiere/graffiti">graffiti</a>. This command
line tool allows to generate a statistics report according to a customisable test
scenario written in YAML. It is now deployed in continuous integration on qgis4 server to generate
<a href="http://tests.qgis.org/perf_test/graffiti/">daily performance reports</a>.

<hr/>
# Point Clouds

Due to my strong interest in point cloud technologies, I'm also involved in:

  + {:.item} <a href="https://github.com/pgpointcloud/pointcloud">PgPointCloud</a>: core committer, LAZ compression
  + {:.item} <a href="https://github.com/PDAL/PDAL">PDAL</a>: revert Morton algorithm
  + {:.item} <a href="https://github.com/LASzip/LASzip">LASzip</a>
