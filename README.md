

<h3>Screenshots</h3>

![alt text](https://github.com/sharmaachintya08/pictures/blob/master/1.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/2.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/3.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/4.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/5.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/6.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/7.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/8.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/9.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/10.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/11.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/12.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/13.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/14.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/15.jpeg)<br/>
![alt text](https://github.com/sharmaachintya08/pictures/blob/master/16.jpeg)<br/>

## It makes use of following:-
- **LiveData & MutableLiveData** for updating and listening to realtime datachanges in app. Also livedata can survive configuration changes.
- **ViewModel** with **ViewModelFactory** to acess livedata
- **Repository** as **single source of truth** to make Database operations
- **Coroutines** to perform databse operations in background thread without blocking main thread.
- Various Coroutine Context based on type of operation: e.g Dispatchers.Main for updaing UI in main htread and Dispatchers.IO to work in background thread.
- Also, database dao methods are defined suspend fun methods so that they run in background thread. This work is done internally by Room library automatically.
- Also, LiveData in ViewModel are update in viewModelScope, a Coroutine scope provided for livedata.

- **ConstraintLayout** for maki device compatible ui in screen.
- **BottomSheet** a material design ui component for opening a bottomsheet
- **BottomNavigationView** another material design ui component for changing tabs

***
<p> <img src="https://developer.android.com/codelabs/android-training-livedata-viewmodel/img/fd28069527c8d615.png"> </p>
