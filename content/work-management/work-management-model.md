# A Work Management Model for Software Development

* ... provides a consistent set of terms and definitions to manage work systematically
* ... a model out of many possible
* ... technically applicable to other domains than software development.


## Intentions and Goals


## Work Management Scope


### Product


## Work Item

* A work item represents work to achive an intended/expected result.

* Content of a work item is a description of the intended result (mandatory)
  and how to achieve it (optional); depending on the kind of work and applicable conventions
  there's a degree of freedom for the when it's obv optionally instructions or just hints has a specific content

* Executing a work item represents doing the work and achive a result
  \- it may be the expected result or a different one.


## Work Item Hierarchy

Work is managed on multiple levels (TODO: of abtraction?):

* There's one level where the fundamental software development work resides,
  e.g. software design, software documentation, feature development, bugfixing, etc.
  * A work item represents the 'unit of work on this level.
  * Executing a work item means doing
* 'Above' the work item level

Those different levels of work management form a hiearchy where ...


### Work Item


### Organizational Work Item

* ... represents a larger body of work which cannot be executed 'in one go'.
  To manage such work properly the orgainzational work item needs to be split
  into multiple work items of the next lower level.
* Other than a work item an organizational work item can't be executed by itself;
  instead, it is excuted by (TODO) doing the lower-leve work items it has been split itno.


### Task

* Part of a work item; represents some work or activity which is not managed by itself
  but as part of a work item.
* Not considered an actual work item by the definition of this model.


### Comparison of Organizational Work Item, Work Item and Task

|   | Organizational Work Item | Work Item | Task |
| - | ------------------------ | --------- | ---- |
|

* Jira -> Issue
* Azure DevOps -> Work Item
* GitHub -> ?
* Gitlab -> ?

 
## References

1) <a name="r1"/>[title](https://link)


----

Last updated: 2024-07-15

Unless otherwise noted, this content is made available under the Creative Commons Attribution 4.0 international license;
additional terms may apply; see [LICENSE](../LICENSE) for details.
