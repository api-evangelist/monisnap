---
title: "💡 Vue Typescript State Management : We can do better than “isLoading” in 2022"
url: "https://dev.to/monisnap/vue-typescript-state-management-we-can-do-better-than-isloading-in-2022-2n5d"
date: "2022-01-04"
author: "Julien"
feed_url: "https://dev.to/feed/monisnap"
---
Sorry for the clickbait title, but I needed your attention 👀 Have you ever encountered code like this one : new Vue ({ el : ' #app ' , data () { return { info : null , loading : true , errored : false } }, filters : { currencydecimal ( value ) { return value . toFixed ( 2 ) } }, mounted () { axios . get ( ' https://api.coindesk.com/v1/bpi/currentprice.json ' ) .
