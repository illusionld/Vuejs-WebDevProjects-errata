---

---

### Template

#### Location:

> _Location path_
>
> [LinkDescription](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    original text that may need to be corrected

#### Proposed change:

    suggested changes go here

---

---

## Chapter 4. Project 3 - Support Center

---

---

### Chapter numbering: Chapter 4 references a previous instance of Chapter 4

#### Location:

> _General app structure > Setting up the project Step 1_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    First, generate a Vue project with the vue init webpack-simple <folder>
    command, like we did in Chapter 4, Advanced Project Setup:

#### Proposed change:

    Chapter 4 should be 5, and Chapter 5 should be 4 if desired result is to have
    Chapter 4: Advanced Project Setup preceding Chapter 5: Project 3 - Support
    Center

#### Related:

    Most the style for the app is already available. Download it
    (https://github.com/Akryum/packt-vue-project-guide/tree/master/chapter5-download)
    and extract the Stylus files into a style folder inside the src
    directory.Extract the assets folder too.

---

---

### Sentence clarity

#### Location:

> _Just above Routing and pages inside Step 1_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    ...and extract the Stylus files into a style folder inside the src
    directory.Extract the assets folder too.

#### Proposed change:

    ...and extract the style and assets folders to your project's src directory.
    The style folder contains the Stylus files which is the CSS language we will be
    using for this project. (http://stylus-lang.com)

---

---

### Slight typo

#### Location:

> _General app structure > Routing and pages_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    A page showing one ticket details and conversation

#### Proposed change:

    A page showing ticket details and conversation for a selected ticket

---

---

### Word exclusion: missing have, has

#### Location:

> _General app structure > Routing and pages > Vue plugins_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    To enable routing in our app, we an official Vue plugin called vue-router.

#### Proposed change:

    ...we have an official Vue plugin...

#### Related issue:

    I recommend the awesome–vue GitHub repository
    (https://github.com/vuejs/awesome-vue) that them by category:

#### Proposed change:

    ...that has them by category:

---

---

### Word exclusion: will

#### Location:

> _General app structure > Routing and pages > Our first routes > Layouts with
> router-view_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    Before adding routes, we need to setup a layout for the app where the route
    components be rendered.

#### Proposed change:

    ...where the route components will be rendered.

---

---

### Typo: styles => style, add a space between the and Setting

#### Location:

> _General app structure > Routing and pages > Our first routes > Layouts with
> router-view_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    After the template, add a style tag importing the main Stylus file from the
    styles folder you downloaded earlier in theSetting up the project section. Don't
    forget to specify that we are using stylus with the lang attribute:

#### Proposed change:

    ...main Stylus file from the style folder you downloaded earlier in the
    Setting up the project section. Don't forget...

---

---

### Typo: Frenquently => Frequently

#### Location:

> _General app structure > Routing and pages > Our first routes > Creating
> routes_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    <template>
        <main class="faq">
          <h1>Frenquently Asked Questions</h1>
        </main>
    </template>

#### Proposed change:

    <template>
        <main class="faq">
          <h1>Frequently Asked Questions</h1>
        </main>
    </template>

---

---

### Word exclusion: routes array

#### Location:

> _General app structure > Routing and pages > Our first routes > The router
> object_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    With our ready, we need to create a router object that will take care of managing the routing for us.

#### Proposed change:

    With our routes array ready, we need to create a router object that will take care of managing the routing for us.

---

---

### Clarification needed

#### Location:

> _General app structure > Routing and pages > Our first routes > The router
> object_
>
> [ch04lvl1sec23](https://www.packtpub.com/mapt/book/web_development/9781787127463/4/ch04lvl1sec23/general-app-structure)

    That is all we need to have routing working! You can now try to change the URL in your browser to either http://localhost:4000/#/ or http://localhost:4000/#/faq and get a different page each time:

#### Proposed change**\***:

    Just noting here that the port number will be different based on configuration. This may be noted in the next Chapter (as it stands, Advanced setup), but if not, it may be worth noting. Will try to remember to come back to this.
