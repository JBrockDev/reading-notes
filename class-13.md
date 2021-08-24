# Class 13 - Reading Notes

## Local Storage

For websites that are entirely front-end especially, a local persistant storage is necessary when you want to allow the current state of the page to be saved between refreshes or the browser being closed and re-opened. Using local storage as opposed to cookies enables the saving of more data as well as the cookie data is sent every HTTP request, which is unnecessary, possibly slower, and even sends the data un-encrypted. 

While any JavaScript variable type may be stored in local storage, the return will be a string so plan accordingly with parsing after retrieving. If a key value pair already exists and you call setItem() on that key, it will overwrite the value assigned. Additionally, if you call getItem() on a key that does not yet exist, you will get null. If at any time you want to clear the local storage entirely, you can call removeItem(existingKeyName) on any key that exists within the local storage. Failure to pass in a key that exists will cause it not to work.
