Preface to the API Design Guide
===============================

**A design guide with developer empathy**.

Like websites, shop-fronts and call centres, web APIs (Application Programming
Interfaces) are just another channel for delivering services online.

Web APIs power many of today’s websites and mobile apps, and are becoming
increasingly important in the digital economy. Web APIs can readily be
incorporated into downstream applications and websites, providing third-parties
an opportunity to reuse and recombine them in creative and value-adding ways.
Good APIs present a digital service as simple building blocks so that the value
of the service can be amplified through third-party reuse.

The principle of user-centred design is at the core of website and application
development. It’s about ergonomics: can a user 'consume a digital service'
without bad design getting in their way? Getting this right requires *user
empathy*, backed by evidence of user preferences. Although a well known
principle, it is not always well practised.

In some ways, *developer empathy* is exactly the same: developers are people
too, and the users of web APIs. The key difference is that when developers use
an API, they often create additional value for many people. A well designed
end-user experience obviously results in a single good user experience. But a
well-designed API on the other hand can result in many good user experiences,
often enjoyed in ways and by those the original service designer did not
envision.


.. epigraph::

   We have developer empathy. If our interfaces are hard to use, we consider
   that a bug.  We are an engineer-led company. Everything we do tries to be
   compatible with our API.

   -- Steve Mayzak, ElasticSearch (around 6.20 into https://www.youtube.com/watch?v=uxfvNwl_MGc).


User empathy is focused on ergonomics at the point of delivery. Developer
empathy is focused on painless systems integration. Good API design is still
fundamentally about ergonomics, but the context is different. As a user,
successful design has the quality of affordance (obviousness, "don't make me
think"). For developers, good API design also incorporates this quality (through
idioms and good documentation).

Good API design allows developers to integrate their applications with your
systems in a decoupled manner; they are able to reuse the resources exposed by
your API in previously unimagined ways. Lastly, good APIs are stable and adhere
the 'principle of least surprise': developers are able to rely on your
API to behave in a predictable manner.

The gold standard in developer empathy is found in thriving open source projects.
Collaboration, peer review and a responsive community are the hallmarks of such
projects. Organisations that do well in this space nurture their relationship
with developers as though their survival depends on it (quite often because it
does). This does not describe Australian Government IT of today, but hopefully
describes the "government as a platform" of tomorrow.

Some things are certain: APIs are important, they can generate additional and
significant value, developer empathy is critical to success and we need all the
help we can get.


The DTO planned to release a draft API design guide describing contemporary best
practices in API design and developer empathy. The final document (API Design
Guide) will inform assessment of conformance against mandatory policy (the
Digital Service Standard) that all Commonwealth agencies must follow, and that
citizens could be entitled to expect. The purpose of releasing a draft was to
get feedback, but at the last minute we had a better idea...

We want feedback from developers, right? So we figured: why not convert it to a
developer-friendly format, publish it in a version control system with a public
ticket system for issues and support, and invite our users to help us make it
better?

Done.

 * read https://apiguide.readthedocs.org/
 * discus https://github.com/AusDTO/apiguide/issues
 * kanban https://waffle.io/AusDTO/apiguide
 * fork https://github.com/AusDTO/apiguide.git

Pull requests welcome!
