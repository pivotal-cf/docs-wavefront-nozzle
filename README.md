# VMware Tanzu Observability by Wavefront Nozzle

## About This Repo

* This is the content repo is for the documentation.
* The content is published to docs.pivotal.io/wavefront-nozzle and docs.pivotal.io/partners/wavefront-nozzle (Soon the partners path will be removed and a redirect added.)

| Branch name | Use for… |
|-------------| -------|
| main      | "edge" branch where new content can be staged and reviewed. Publishes to https://docs-pcf-staging.sc2-04-pcf1-apps.oc.vmware.com/wavefront-nozzle/3-n/ |
| 4.x         | v4.0.0 placeholder page. Publishes to https://docs-pcf-staging.sc2-04-pcf1-apps.oc.vmware.com/wavefront-nozzle/4-x/ and https://docs.pivotal.io/wavefront-nozzle/4-x/ |
| 3.x         | v3.0.0 and later minors. Publishes to https://docs-pcf-staging.sc2-04-pcf1-apps.oc.vmware.com/wavefront-nozzle/3-x/ and https://docs.pivotal.io/wavefront-nozzle/3-x/ |
| 2.x        | v2.1.3, v2.1.2, v2.1.0, and v2.0.0, v2.1.0, v2.1.2, v2.1.3 and later minors. Publishes to https://docs-pcf-staging.sc2-04-pcf1-apps.oc.vmware.com/wavefront-nozzle/2-x/ and https://docs.pivotal.io/wavefront-nozzle/2-x/ |

## Book Repo

The book repo is in [**pivotal-cf/docs-book-wavefront-nozzle**](https://github.com/pivotal-cf/docs-book-wavefront-nozzle).

## Contributing to the Documentation

The docs team prefers to receive documentation contributions as pull requests rather than having engineering teams push directly to the docs repos.
This gives us a chance to review the changes for consistency and understand the new content.
For more information, see [Creating a PR](https://docs-wiki.sc2-04-pcf1-apps.oc.vmware.com/wiki/external/create-pr.html)
in the _VMware Tanzu Docs Wiki._

If you are planning to initiate a large documentation effort, please coordinate with the docs team in advance to make sure we're not going to step on each other.
You can reach the docs team by Slack at #pcf-services-docs.


## Continuous Integration Technical Details

We deploy this documentation as an app using Concourse pipelines on runway:

* [cf-services/wavefront-nozzle](https://runway-ci.eng.vmware.com/teams/mapbu-docs/pipelines/cf-services?group=wavefront-nozzle)
* [cf-services-edge/wavefront-nozzle-edge](https://runway-ci.eng.vmware.com/teams/mapbu-docs/pipelines/cf-services-edge?group=wavefront-nozzle-edge)
