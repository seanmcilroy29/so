# Smart Objects (SO) Working Group Charter

The *Smart Objects Working Group* is responsible for the development and evolution of the Data Model used within OMASpecWorks, specifically on the Device Management WG and Application Objects. It is intended to provide an application-layer (in the OSI model) agnostic data model that can be reused across multiple verticals in the Internet of Things ecosystem.

The *Smart Objects Working Group* will provide a set of data models and schemas necessary for interoperability and will seek to work with other standard bodies to ensure interoperability. The group covers data model definitions for sensors and actuators as well as all metadata they might provide.

|||
|:------------------- | :-----------------------------------|
|**Start Date**       | 15th May 2018 |
|**End Date**         |  TBD |
|**Chairs**           |  TBD |
|**Editors**          |  TBD |
|**Meeting Schedule** |  The group will meet bi-weekly with appropriate calls when needed. The group will also meet during the OMA face-to-face meetings and *asynchronously* on this repository. |
|||

## Deliverables

The group is expected to provide support to the existing IPSO Smart Objects and LWM2M Objects. The group will modify those two object subsets and provide a consistent data model for both.

The group is also expected to deliver guidelines for contribution of new Smart Objects when the existing ones are not sufficient.

The group will provide continuous validation tools for the Smart Objects and maintain them for the lifetime of the Objects.

The group will provide support for Smart Objects users via the Issue Tracker and mailing lists.

The group will look at existing standards and practices within the industry and identify opportunities for new work.

## Coordination

The WG will seek for a complete review for all its deliverables, within OMA SpecWorks and across selected specialists, specifically on topics like interoperability, application development, privacy, and security. Invitation for review must be issued before each major data model transition.

The SO Working Group will coordinate with the OMA DM Working Group when it comes to the modification of the LWM2M Objects used for management of Devices (i.e. LWM2M Objects on Device, Server, Security ...) and with the [Open Mobile LWM2M Object and Registry](http://www.openmobilealliance.org/wp/OMNA/LwM2M/LwM2MRegistry.html) to provide a single registry for developers and applications.

Additional technical coordination can be sought on an ad-hoc basis with the following organisations, the list is not exhaustive and organisations can change: IETF Core Working Group, OneM2M, Open Connectivity Foundation, W3C WoT Group, Industrial Internet Consortium, Fairhair Alliance.


## Participation

The group will participate in a collaborative fashion over github. Pull Requests will be the main form of contribution, in addition to comments, questions, presentations and mailing lists.

The group welcomes non-Members to contribute technical submissions, issue tracker comments and other feedback for consideration. With the implicit agreement from each participant to the [LICENSE](https://github.com/omadm/so/blob/master/LICENSE).

### Consensus Process

Changes to Objects will be reviewed by an expert review committee and by the group. Purely editorial changes might be made by appointed Editors without group consensus.

Major updates on the model, the schema or specification changes will be done within the OMA SpecWorks organisation and follow its review process. As stated in the **Coordination Section** the group will seek a complete review as part of the final consensus process.

The response period for the consensus call will be left to the chair, with no less than 7 work days for review.


### Contributor Workflow

Every individual member can contribute patch proposals using "pull requests" and expect a response. This facilitates social contribution, easy testing and peer review.

To contribute a patch, the workflow is as follows:

1. Fork repository
2. Create topic branch
3. Commit patches

Please refer to the [Git manual](https://git-scm.com/doc) for more information about Git.

Changes that require consensus are:

* `Specification` for changes that affect the SO specification.
* `Tools` for changes to tools used within the group (e.g. validation, implementations...).
* `XML` for changes to specific objects. Can be other object format.
* `XSD` for changes to the schema. Can be other schema format.

Changes that do not require consensus are:

* `editorial` for editorial changes on the specification (e.g. comments, whitespace, etc.). Any change to an object is not editorial.
* `new so` for new objects and resources that are not already specified. These will require only the approval of the chairs or editors.

Every pull request should contain a summary and the changes, for example:

```
Specification: Edited the data type to add MY_DATA_TYPE.
XML: Added a new Resource to Object 3303.
Tools: improve the validation mechanism with a new test.
```
Changes that do not require consensus should not be mixed with those that do.

Pull requests will be closed by the group either online or during the by-weekly meetings. A PR can be **closed online** with a simple majority from the group and reviewers, as long as no negative reviews remain on the PR.

The chairs can assign specific reviewers for any PR, reviewers MUST provide feedback on the PR before it gets merged.

## License

The group will use the license below for all its deliverables.
<https://github.com/omadm/so/blob/master/LICENSE>

**N.B.**: The charter might be changed or reviewed at the group's consideration.
