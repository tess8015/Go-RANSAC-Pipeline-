# Optimizing RANSAC Algorithm with Concurrent Threads in Go
This project is dedicated to elevating the efficiency of the RANSAC algorithm through concurrent threads in the Go programming language. My focus was concurrency to amplify the execution speed of the RANSAC algorithm.

## Key Features

#### RANSAC Algorithm: 
The RANSAC algorithm facilitates noise-resistant parameter estimation from datasets. Through concurrent threads, we seek to trim down its execution time.

#### Goroutines and Channels: 
I employed Go's goroutines for simultaneous execution and channels for seamless communication and synchronization between threads.

#### WaitGroups: 
I levereged the sync package's WaitGroup functionality to ensure orderly synchronization of goroutines, guaranteeing completion before proceeding.
