# TODO - Tests

## checksExistsUserAccount
[x] - it should be able to find user by username in header and pass it to request.user

[x] - it should not be able to find a non existing user by username in header

## checksCreateTodosUserAvailability
[x] - it should be able to let user create a new todo when is in free plan and have less than ten todos

[x] - it should not be able to let user create a new todo when is not Pro and already have ten todos

[x] - it should be able to let user create infinite new todos when is in Pro plan

## checksTodoExists
[x] - it should be able to put user and todo in request when both exits

[x] - it should not be able to put user and todo in request when user does not exists

[x] - it should not be able to put user and todo in request when todo id is not uuid

[x] - should not be able to put user and todo in request when todo does not exists


## findUserById
[x] - it should be able to find user by id route param and pass it to request.user

[x] - it should not be able to pass user to request.user when it does not exists
