<template>
    <Crud />
</template>

<script>
import PageViewer from './components/PageViewer';
import Crud from './components/CRUD';


  export default {
    components: {
        PageViewer,
        Crud
    },
      data() {
          return {
              activePage: 0,
              pages: [
                  {
                      link: {text: 'Home', url: 'index.html'},
                      pageTitle: 'Home Page',
                      cotent: 'This is the home content'
                  },
                  {
                      link: {text: 'About', url: 'about.html'},
                      pageTitle: 'About Page',
                      cotent: 'This is the about content'
                  },
                  {
                      link: {text: 'Contact', url: 'contact.html'},
                      pageTitle: 'Contact Page',
                      cotent: 'This is the contact content'
                  }
              ]
          }
      }
  }
</script>