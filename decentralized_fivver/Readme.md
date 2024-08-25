<!-- # Setup the project

## You must have a Phantom Wallet with some devnet solana in it

#### cd into backend directory then run npm run dev

#### Then cd into root directory then go to user_frontend directory then run npm run dev to start

### Finally cd into root directory and then go to worker_frontend directory then run npm run dev


# Aim of this project

#### This is a data labelling platform where one can upload a bunch of data(like thumbnail for youtube) call them task and pay some amount of sol which goes into the parent wallet 

#### Now the users (let's call them worker) will vote the most appropriate thumbnail and for that they are paid some amount of sol from the amount which was paid by the task creator

#### The worker will have some amount of sols which worker has made by voting some tasks which he can withdraw by clicking withdrawing button.

#### The amount that the worker will withdraw will be taken from the parent wallet



# Technologies used

1) Express.js for backend
2) Prisma as a sql database
3) Nextjs for both user and worker frontend
4) @solana/web3.js for wallet connection and payments
5) socket.io for showing vote count in real time

 -->


### Backend Setup

• Navigate to the backend directory:
  cd backend

• Start the backend server
  npm run dev



### User Frontend Setup

• Navigate to the user_frontend directory:
  cd ../user_frontend

• Start the user frontend server:
  npm run dev


#### Worker Frontend Setup

• Navigate to the worker_frontend directory:
  cd ../worker_frontend

• Start the worker frontend server:
  npm run dev



# Project Aim

This platform allows users to upload data (e.g., YouTube thumbnails) as tasks, for which they pay in SOL (Solana cryptocurrency). Workers on the platform vote on the best submissions and earn SOL for their participation. The SOL used for payments and withdrawals is managed by a parent wallet.


## Workflow: 

• Task Creation: Users upload tasks and pay in SOL, which is stored in the parent wallet.

• Voting: Workers vote on tasks. For each vote, they earn a portion of the SOL paid by the task creator.

• Withdrawal: Workers can withdraw their earnings, which are deducted from the parent wallet.


## Technologies Used

1) Express.js: Backend server
2) Prisma: SQL database management
3) Next.js: Frontend framework for both user and worker interfaces
4) @solana/web3.js: Solana wallet connection and payment processing
5) Socket.io: Real-time vote count updates
6) Everything is written in typescript