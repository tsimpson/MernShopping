## Client Side

Frontend for Shopping List App

## To Use:
In Main Directory run:

`npm run client-install`

## Starting Client and Server:
In the Main Directory, you can use these scripts to start client and server separate, or together:

### Server:
`npm run server`

### Client:
`npm run client`

### Together:
`npm run dev`
This one uses a package called `concurrently` to run both together, which is nice if you don't want to use multiple terminals.

### Dependencies:
____
* redux - state container
* react-redux - To tie react/redux together
* redux-thunk - middleware to write action creators that return a function instead of an action.