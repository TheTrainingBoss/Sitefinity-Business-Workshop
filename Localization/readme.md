Localization
============

Localization allows you to display your website in any language. The
ability to localize your entire site to any language is baked right
into Sitefinity. Not only text, but any other content relevant to the
culture of your website visitor is configurable. The back- end of the
website is also fully localizable. All menu items, button text,
labels, etc. are localizable. Search for \"Language Packs\" here:

[*http://www.sitefinity.com/marketplace/modules.aspx.*](http://www.sitefinity.com/marketplace/modules.aspx)

##### Localizing Front End Pages

In this next walk through we will add the Spanish language and
localize a front-end page to reflect the language choice.

1.  Select the administration menu Settings option.

2.  From the list on the left side of the page select the Languages
    option.

3.  Click the Add languages\... button.

4.  Use the search box to locate *Spanish* in the list and select the
    check box.

![](../media/image524.png)

5.  Click the Done button. Now the new *Spanish* language entry shows up
    under the default *English* entry.

![](../media/image525.png)

Below the Languages for public content section is the Default language
for the backend system. You can change the language for the backend
system by clicking the Manage backend languages link and adding
languages there. Leave the default setting for this example.

6.  Click the Save changes button.

Select the administration menu Pages option. This option will take
extra time because Sitefinity needs to accommodate the new languages
by making database changes. When the list refreshes, all the pages in
the site are \"localization ready\" and have a new Translations
column.

![](../media/image526.png)

7.  Click the ES Add link for the home *Welcome* page (if you don't have
    the page built, go ahead and create a welcome page now).

![](../media/image527.png)

8.  Create a page (ES) displays so you can supply a new page Name, URL
    and Title in the appropriate language.

![](../media/image528.png)

9.  Click the Create and go to add content button.

10. At this point your options are Copy from another language, or Start
    from Scratch. The first option is especially productive if you have
    images that you want to copy between versions. Click the Copy from
    another language link.

11. The Copy content from another language dialog displays. The English
    language is the only version available for this page, so the drop
    down list is disabled. Select the Keep all language versions synced
    check box. Click the Done button to close the dialog.

![](../media/image529.png)

The translated page displays. Notice the message at the top of the
page that lets you know that the pages are synced and what kind of
behavior you can expect while designing the page.

![](../media/image531.jpeg)

12. Click the content block Edit button (if you don't have a Content
    Block on the page, add one now).

13. Paste *Bienvenido a CarConduit!* into the editor window. Click the
    Save button.

14. Click the Publish button. Note that publishing pushes out all the
    translations.

15. View the page. Notice the URL in the address bar uses the culture
    code *es*. The translated content shows at the head of the page.

![](../media/image533.png)

##### User Language Selection

You can use the Language selector widget right in your page so that
the user can dynamically choose the language they want to view the
page in.

1.  Open the localized page for editing again.

2.  Open the Navigation section of the right hand menu. Drag the
    Language selector widget to the top of the page.

3.  Click the language selector widget Edit button. In the Display
    language selector as\... option, select Drop-down menu.

Also notice the checkbox option to include the current language in the
selector.

What to do with languages without translations? Your options are to
Hide the link to the missing translation or Redirect to the home
page\...

![](../media/image535.png)

4.  Click the Save button to close the dialog.

Publish and view the page. Use the drop down language selector to show
both translations of the page.

![](../media/image536.png)

#### Next Topic
[Page Administration](../Page%20Administration/readme.md)