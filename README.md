```
submitAction: ({ data, callbacks = [] }) => dispatch => new Promise((resolve, reject) => dispatch({
    type: 'submit',
    data,
    reject,
    resolve,
    callbacks,
  }))

 Creators.submitAddressForm({ data, callbacks })(dispatch)
   
```
