.. _Developing Course Sections:

###################################
Developing Course Sections
###################################

To develop sections in your course, you must first understand the following:

* `What is a Section?`_
* `Viewing Sections in the Outline`_
* `The Student View of a Section`_
* `Sections and Visibility to Students`_
* `Release Statuses of Sections`_

  
Section tasks:

* `Create a Section`_
* `Change a Section Name`_
* `Set a Section Release Date`_
* `Delete a Section`_


****************************
What is a Section?
****************************

A section is the topmost category in your course. A section can represent a
time period in your course, a chapter, or another organizing principle. A
section contains one or more subsections.

********************************
Viewing Sections in the Outline
********************************

The follow example shows four sections, all collapsed, in the course outline:

.. image:: ../Images/sections-outline.png
 :alt: Four sections in the outline

******************************
The Student View of a Section
******************************

Students see sections in the Courseware tab, at the top level of the left-hand
navigation tree. Students can expand one section at a time to see its contents.
In the following example, two sections are circled, and the second one is
expanded to show its subsections:

.. image:: ../Images/sections_student.png
 :alt: The students view of the course with two sections circled

************************************************
Sections and Visibility to Students
************************************************

Students never see a section that has an unscheduled or future release date.

If the release date of the section has passed, students see content according
to the release date of the subsections and the publish state of the units.

Students do not necessarily see all content in a released section. Students may
not see content in:

* A subsection, if its release date is in the future.
  
* A unit, if it was never published, or if it is hidden from students.

************************************************
Release Statuses of Sections
************************************************

As an course author, you control the release status of sections.  For the
content of a section to be visible to students, the section must be released.
See the following for more information about the possible releases statuses of
sections:

* `Unscheduled`_
* `Scheduled`_
* `Released`_
* `Released with Unpublished Changes`_
* `Staff Only Content`_

========================
Unscheduled
========================

If you do not change the :ref:`course start date<The Course Start Date>`
default value, ``12/31/2029``, when you create a new section, it's release date
will be ``Unscheduled``. When you section release date is ``Unscheduled``,
students cannot see any content in that section, regardless of the release
status of content within the section.

If you have modified the course start date, when you create a new section, the
default release date is the course start date.

The following example shows how an section in the Unscheduled state is
displayed in the outline, with a gray bar:

.. image:: ../Images/section-unscheduled.png
 :alt: An unscheduled section

To make the content available to students, you must schedule the release date.

==========
Scheduled
==========

A section that is scheduled for release on a future date will not be visible to
students until after the release date. Regardless of the state of content
within the section, the entire section will not visible to students.

The following example shows how a section that is scheduled for release is
displayed in the outline, with a green bar:

.. image:: ../Images/section-future.png
 :alt: An section scheduled to release in the future

The scheduled date must pass for the section to be visible to students.

===========================
Released
===========================

A section that is released is visible to students; however students see only
subsections within the section that are also released, and units that are
published.

The following example shows how an section in the released state is displayed
in the outline, with a blue bar:

.. image:: ../Images/section-released.png
 :alt: An unscheduled section

==================================
Released with Unpublished Changes
==================================

If you change a unit in a released section but do not publish the changes, the
section status becomes ``Released with Unpublished Changes``.  In this
situation students view the last published version of the modified unit.

The following example shows how an section that has unpublished changes is
displayed in the outline, with a yellow bar. The section is expanded to show
the unit with unpublished changes:

.. image:: ../Images/section-unpublished-changes.png
 :alt: A section with unpublished changes

You must publish the unit for students to see the updates.

===========================
Staff Only Content
===========================

A section can contain a unit that is hidden from students and available to
staff only. That unit is not visible to students, regardless of the release
date of the section or subsection.

The following example shows how a section that contains a unit that is hidden
from students is displayed in the outline, with a black bar:

.. image:: ../Images/section-hidden-unit.png
 :alt: A section with a hidden unit 


.. _Create a Section:

****************************
Create a Section
****************************

If you do not change the :ref:`course start date<The Course Start Date>`
default value, ``12/31/2029``, when you create a new section, it's release date
will be ``Unscheduled``. 

If you have modified the course start date, when you create a new section, the
default release date is the course start date.

.. caution:: 
 If the course start date is in the past, newly created sections are
 immediately visible to students.

To create a new section:

#. Click **New Section** at the top or bottom of the outline: 
   
   .. image:: ../Images/outline-create-section.png
     :alt: The outline with the New Section buttons circled

   A new section is added at the end of the course content, with the section
   name selected.

#. Enter the name for the new section. Remember that students see the section
   name in the courseware.

#. :ref:`Add subsections<Create a Subsection>` to the new section as needed.
   
It is recommended that you :ref:`test course content <Testing Your Course
Content>` as you create new sections.

********************************
Change a Section Name
********************************

To edit a section name, hover over the section name to show the Edit icon:

.. image:: ../Images/section-edit-icon.png
  :alt: The Edit Section Name icon

Click the Edit icon next to the section name. The name field becomes writable.
Enter the new name and tab or click out of the field to save the name.

.. _Set a Section Release Date:

********************************
Set a Section Release Date
********************************

To set the section release date:

#. Click the Settings icon in the section box:
   
   .. image:: ../Images/section-settings-box.png
    :alt: The section settings icon circled

   The Settings dialog box opens.

#. Enter the release date and time for the section:
   
   .. image:: ../Images/section-settings.png
    :alt: The section release date settings

#. Click **Save**.

For more information, see :ref:`Release Dates`.


********************************
Delete a Section
********************************

When you delete a section, you delete all subsections and units within the
section.

.. warning::  
 You cannot restore course content after you delete it. To ensure you do not
 delete content you may need later, you can move any unused content to a
 section in your course that you set to never release.

Click the delete icon in the box for the section you want to delete:

.. image:: ../Images/section-delete.png
 :alt: The section with Delete icon circled

You are prompted to confirm the deletion.