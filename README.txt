=== Woordle ===
Contributors: zero62
Donate link: https://zero62.com
Tags: moodle, lms, courses, lessons, online learning, learning management system
Requires at least: 5.0
Tested up to: 5.1.1
Stable tag: 0.9.2
Requires PHP: 5.6.*
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Wordle is the best online school management system for WordPress.

== Description ==

Wordle is the best online school management system for WordPress.

With Woordle, you can earn online courses, sell them using Woocommerce, and migrate them to Moodle. All in a simple and fast way.

Features:

* Create courses in a simple way
* Configure how your course will be migrated to Moodle. (topics, social, etc.)
* Sell ​​your course with Woocomemrce.
* Apply promotions, discount coupons on the product of your course.
* Simple enrollment process with a click, your students can enroll
* Enrollment approval. You can set whether your subscriptions will be automatically released or require moderator approval.
* Automatic Migration of Moodle enrollments, whenever it is published.

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files to the `/wp-content/plugins/woordle` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Woordle -> Settings screen to configure the Moodle connection and more.


== Frequently Asked Questions ==

= Am I required to have Woocommerce installed? =

No, but without Woocommerce, you will not be able to apply any type of charges in the registrations.

= How do I set up Moodle to receive my courses and students? =

You should set up a webservice. You can see our documentation [here](https://docs.moodle.org/36/en/Using_web_services)

= What functions should I enable in the Moodle webservice? =

You should enable the functions below:

* `core_course_create_categories`
* `core_course_create_courses`
* `core_course_get_categories`
* `core_course_get_courses`
* `core_course_get_courses_by_field`
* `core_course_update_categories`
* `core_course_update_courses`
* `core_user_create_users`
* `core_user_get_users`
* `enrol_manual_enrol_users`

= How to the students can do login in Moodle? =

When a user is created in Moodle by Woordle, a password is generated and sent to the registered email. Therefore, it is important that the email service is functioning properly on your server.


== Screenshots ==

screenshot-1.png
screenshot-2.png
screenshot-3.png
screenshot-4.png
screenshot-5.png
screenshot-6.png
screenshot-7.png
screenshot-8.png
screenshot-9.png
screenshot-10.png

== Changelog ==

= 0.9.2 =
    * Improved WordPress documentation

= 0.9.1 =
    * Fix bugs and improvements

= 0.9.0 =
    * Created single course page
    * Created archive course page

= 0.8.0 =
    * Sync enrolment with Moodle
    * Added my courses tab in Woocommerce My Account
    * Added Student Central shortcode

= 0.7.0 =
    * Syncing users wth Moodle
    * Fixing bugs

= 0.6.0 =
    * Syncing course category wth Moodle
    * Syncing courses with Moodle

= 0.5.0 =
    * Added option for setup auto enrolment

= 0.4.0 =
    * Created enrolment by Woocommerce checkout process
    * Saving enrolment in draft status

= 0.3.1 =
    * Created enrollment metabox
    * Created simple enrolment process
    * Added enrolment info in metabox

= 0.3.0 =
    * Created enrolment Post type

= 0.2.2 =
    * Allow user define if sale course with Woocommerce
    * Integrate Course with Woocommerce
    * Added Enrolment tab in course form
    * Start initial course template
    * Created Course product type in Woocommerce
    * Added tab with course info in product form

= 0.1.2 =
    * Created Woordle settings options
    * Added promotional tab in course form
    * Improved Woordle in admin (Create exclusive menu)
    * Improved Course form
    * Fix bug on save Courses

= 0.1.0 =
    * Init plugin core
    * Register Course post type
    * Created Course form
    * Added Course Category taxonomy
    * Created Course Category form

