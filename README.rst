Inclusive Language at Dialpad
=============================

.. contents:: :local:

Motivation
----------

The language we use is a simple but tiny corner of being inclusive of all employees, and we recognize that there is still terminology in the tech industry and at our company that has problematic origins or connotations. Every employee has the right to work in an environment where they are respected, included and valued. This document provides a list of recommendations for inclusive language, based on research by the linguists of Dialpad.

Internal discussion of inclusive language has resulted in the creation of this document. It seeks to provide concrete actions to encourage company-wide and context-independent use of language that includes everyone. That being said, this is a living document that will always need multiple perspectives to achieve its goals. Please bring up your thoughts or concerns about this document with any manager; we welcome every contribution.

The terminology in question falls broadly into two categories; technical vs day-to-day language. The former involves terms that may or do currently show up directly in code or in technical documentation; the latter includes terms that arise in everyday speech, and might result in some listeners feeling excluded. Both sections are relevant to engineering teams but other non-engineering teams will be most interested in the second section. Following the list of suggested replacements, we discuss the use of these recommendations going forward. At the end of the document we've included an appendix expanding on the reasons for which particular terms have been considered for replacement.

Proposed replacements
---------------------

Technical language
~~~~~~~~~~~~~~~~~~

+----------------------------------+---------------------------+-------------------------------+
| Term                             | Recommended alternative   | Read more here                |
+==================================+===========================+===============================+
| "whitelist"                      | allowlist                 | `"Bad is Black" effect`_      |
+----------------------------------+---------------------------+-------------------------------+
| "blacklist"                      | denylist                  | `"Bad is Black" effect`_      |
+----------------------------------+---------------------------+-------------------------------+
| "master" (git repository)        | main                      | `"Master/slave" terminology`_ |
+----------------------------------+---------------------------+-------------------------------+
| "master/slave" (nodes)           | coordinator/worker        | `"Master/slave" terminology`_ |
+----------------------------------+---------------------------+-------------------------------+
| "master/slave" (databases)       | primary/replica           | `"Master/slave" terminology`_ |
+----------------------------------+---------------------------+-------------------------------+
| "ghetto test"                    | smoke test                | `Etymology of "ghetto"`_      |
+----------------------------------+---------------------------+-------------------------------+
| "dummy value"                    | placeholder               | `Ableist language`_           |
+----------------------------------+---------------------------+-------------------------------+
| "sanity check"                   | confidence check          | `Ableist language`_           |
+----------------------------------+---------------------------+-------------------------------+
| "male/female connectors"         | plug/socket               | `On sex and gender`_          |
+----------------------------------+---------------------------+-------------------------------+
| "mother/daughter nodes"          | parent/child nodes        | `On sex and gender`_          |
+----------------------------------+---------------------------+-------------------------------+
| "sister nodes"                   | sibling nodes             | `On sex and gender`_          |
+----------------------------------+---------------------------+-------------------------------+
| "mom test" / "girlfriend test" / | user testing              | `On sex and gender`_,         |
| "granny test"                    |                           | `Ageism in tech`_             |
+----------------------------------+---------------------------+-------------------------------+
| "black / white hat hacking"      | ethical/unethical hacking | `"Bad is Black" effect`_      |
+----------------------------------+---------------------------+-------------------------------+
| "dead man's switch"              | death switch              | `On sex and gender`_          |
+----------------------------------+---------------------------+-------------------------------+

Non-technical language
~~~~~~~~~~~~~~~~~~~~~~

+----------------------------------+---------------------------+-------------------------------+
| Term                             | Recommended alternative   | Read more here                |
+==================================+===========================+===============================+
| (generic) "she" / "he"           | they                      | `On sex and gender`_          |
+----------------------------------+---------------------------+-------------------------------+
| (generic) "her" / "him" /        | their                     | `On sex and gender`_          |
| "him or her" / "him/her"         |                           |                               |
+----------------------------------+---------------------------+-------------------------------+
| (generic) "hers" / "his" /       | theirs                    | `On sex and gender`_          |
| "his or her" / "his/her" /       |                           |                               |
| "his/hers"                       |                           |                               |
+----------------------------------+---------------------------+-------------------------------+
| "mankind"                        | people / humankind /      | `On sex and gender`_          |
|                                  | society                   |                               |
+----------------------------------+---------------------------+-------------------------------+
| "manpower"                       | effort                    | `On sex and gender`_          |
+----------------------------------+---------------------------+-------------------------------+
| "man-hours"                      | hours of effort /         | `On sex and gender`_          |
|                                  | person-hours              |                               |
+----------------------------------+---------------------------+-------------------------------+
| "man-months"                     | months of effort /        | `On sex and gender`_          |
|                                  | person-months             |                               |
+----------------------------------+---------------------------+-------------------------------+
| "grandfathered" /                | legacy status             | `The history of               |
| "grandfather clause"             |                           | "grandfathering"`_            |
+----------------------------------+---------------------------+-------------------------------+
| "ghetto share"                   | double screenshare        | `Etymology of "ghetto"`_      |
+----------------------------------+---------------------------+-------------------------------+
| "middle man"                     | intermediary              | `On sex and gender`_          |
+----------------------------------+---------------------------+-------------------------------+

Using these recommendations
---------------------------

Our goal is to switch to inclusive language at our company at every level - in our daily conversations with teammates and customers, our user-facing documentation, our internal technical documentation and our code. Additions to any of these areas must avoid the non-inclusive language in this guide, and any older code or documentation should be updated as soon as is feasible.

For engineers
~~~~~~~~~~~~~

All new code that goes into our codebase must avoid the non-inclusive language in this guide.

Please feel empowered to fix any non-inclusive language that exists in our codebase. The management team is working to do this, but please fix or call out anything that continues to exist.

Some code might be hard to fix right away (such as database model names). When that happens please open a ticket to track it, and leave a comment on the code so we can identify these easily, e.g., "TODO(inclusivity): #TicketNumber your comment here"

Appendix: Explanations
----------------------

"Bad is Black" effect
~~~~~~~~~~~~~~~~~~~~~

"Blacklist/whitelist" and "black/white hat hackers" play into the metaphor of black = bad and white = good. `Research <https://www.scientificamerican.com/article/the-bad-is-black-effect/>`_ has found that this type of metaphor contributes to implicit bias so it is good to avoid. Additionally, "allow" and "deny" are more transparent in meaning than "black" and "white".

Singular they
~~~~~~~~~~~~~

"They/them/theirs" has been used as a 3rd person singular pronoun when the gender of the person is unknown or explicitly unspecified `since the 15th century AD <https://www.oed.com/view/Entry/200700>`_. Despite what self-styled grammar mavens may tell you, we linguists give you full permission to use these pronouns everywhere when you are talking about a generic user or developer, to be inclusive of everyone. Please refer to `On sex and gender`_ for more information on gender.

It is important to remember, though, that when referring to specific individuals, inclusive practice is to use the pronouns they have asked you to use to refer to them! For example, if Vasundhara uses she/her and xe/xyr pronouns, you should say, "She loves birds," or "Xe wrote a song about trilobites."

On sex and gender
~~~~~~~~~~~~~~~~~

Moving away from language that centres men signals inclusion of all genders. There are many good alternatives that refer to a generic person without the connotation that maleness is the "default" gender. Please ensure that you use gender-inclusive language in code, technical documentation and user-facing documentation like our website and support pages.

Anatomical sex, gender (identity), gender expression and sexuality are distinct concepts that often get confused or conflated. Refer to `the Gender Unicorn <http://www.transhealthsa.com/wp-content/uploads/2017/05/The-Gender-Unicorn.pdf>`_ for a quick summary of the concepts. Pronouns are a form of gender expression which is not directly predictable from someone's gender (e.g., a woman who uses they/them pronouns) or their appearance. Read more in this `IBM blog post about pronouns <https://www.ibm.com/blogs/think/2020/07/gender-pronouns-how-small-words-make-a-big-difference/>`_ and in this `blog post about pronouns by nonbinary linguist Dr. Kirby Conrod <https://kconrod.medium.com/ask-a-linguist-about-pronouns-8add318fbd67>`_.

"Male" and "female" connectors are needlessly related to anatomical sex (genitalia). It's unclear that this terminology should be in the workplace and we can do better with the alternative "plug" and "socket".

"Master/slave" terminology
~~~~~~~~~~~~~~~~~~~~~~~~~~

"Master/slave" terminology in tech alludes to the horrific practice of `slavery <https://www.history.com/topics/black-history/slavery>`_. Especially in the North America, the history of slavery is very recent, very racialized and thus a source of pain to Black people. Many Black developers have asked for the change to be made because they find the term personally offensive and many non-Black developers also find the term inappropriate (see final paragraph of this section). This is not a new thing - people have been against this terminology for decades; see for example `this news article about "master/slave" terminology from 2003 <https://www.cnn.com/2003/TECH/ptech/11/26/master.term.reut/>`_.

You may be surprised to learn that the "master" branch in the version control software git `comes from the "master/slave" concept <https://mail.gnome.org/archives/desktop-devel-list/2019-May/msg00066.html>`_, and not from master copy. In light of this problematic and painful history, it's a good idea to move away from this terminology.

In the context of nodes, we want to differentiate between special nodes that tell other nodes what to do (the "special" node can create more worker nodes, take them down when unused, distribute work between them, etc.).

In the context of databases, on the other hand, we want to differentiate between the main database and several copies of it - "primary/replica" communicates this transparently. Note that some systems have already made the decision to implement alternate terminology which constrains us to use the commands they provide. For example, Redis chose "master/replica" terminology and this is reflected in their commands.

This `qualitative tweet thread <https://twitter.com/zkat__/status/1272603164454162432>`_ sparked by Microsoft senior software engineer Kat Marchán about the "master" branch name in Git, has many interesting responses from Black developers in industry. Most of their responses say that they support the change. One Black developer even said, "The combination of master/slave is highly problematic and I feel something really negative and triggering every time someone uses those phrases in my presence." While some people may not be personally offended by the terminology, it is useful to consider `the difference between offense and harm <https://twitter.com/btanderson72/status/1279507428128718848>`_.

Etymology of "ghetto"
~~~~~~~~~~~~~~~~~~~~~

The term "ghetto" has particularly `racist connotations against Black people in the US <https://time.com/5684505/ghetto-word-history/>`_, where many of our employees live and work. It originally meant a part of the city where minority groups lived, then it was used to describe walled-off places where Jewish people were kept in Nazi Germany. But the US's much more recent history of segregation has changed the meaning. When used as an adjective, it is used to convey "unruly" or "uncouth" behaviour, and given the inextricable link to segregation and US history, this `perpetuates problematic ideas that stigmatize Black people <https://blackcommentator.com/132/132_guest_ghetto.html>`_.

Ableist language
~~~~~~~~~~~~~~~~

Ableism, discrimination and prejudice against disabled people, is pervasive in our society and the language we use is a part of the bigger problem of "systematically devaluing bodies and minds that are deemed deviant, abnormal or defective," according to disability activist Lydia X. Z. Brown. Her website includes a detailed discussion of `ableist language and alternatives for a general audience <https://www.autistichoya.com/p/ableist-words-and-terms-to-avoid.html>`_.

"Dummy" has an offensive (but dated) connotation towards people who are dumb (cannot speak). More broadly, `conflating mental illness with "bad" or "less" is ableist <https://medium.com/@ProfBanks/evil-isnt-a-mental-illness-5015263985ca>`_. The suggested alternatives do not perpetuate ableism, and are also more accurate.

Ageism in tech
~~~~~~~~~~~~~~

The idea behind user testing is to get users unfamiliar with the product to test it and give you feedback. "User testing" communicates that idea without perpetuating sexist and ageist ideas about who can use our applications, compared to "granny testing".

Assuming that older people cannot use technology or cannot use our application is harmful because it reinforces `tech's existing problem of ageism <https://www.indeed.com/lead/tech-ageism-report>`_. This is a form of bias against older people that is not often talked about in tech but has been quantified - there is an `age-linked salary ceiling <https://insights.dice.com/2019/06/24/ageism-tech-professional-earnings/>`_ and `barriers to entry and retention <https://bdtechtalks.com/2019/03/29/ageism-in-tech-age-limit-software-developers-face/>`_.

The history of "grandfathering"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The term "grandfather clause" comes from the US and slavery - it was a clause in the US constitution `to prevent Black people from voting <https://www.npr.org/sections/codeswitch/2013/10/21/239081586/the-racial-history-of-the-grandfather-clause>`_. This is a case where in addition to the original term having problematic origins, we should make this change also because the alternative "legacy status" is clearer in meaning.
