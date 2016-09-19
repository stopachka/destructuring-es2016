---
title: TODO
layout: javascriptexercise-layout:javascriptexercise
layout_data:
---

function* dataConsumer() {
    console.log('Started');
    console.log(`1. ${yield}`); // (A)
    console.log(`2. ${yield}`);
    return 'result';
}
