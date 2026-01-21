# Profit finding based on options

- Assumption: Analysis is based on Taiwan Index option data as of Sep 17,2025 and that current index is 25,432.11
  

## Scenario 1

If we are sure that when options expire, Taiwan Index will be above 25,650. 

## Scenario 2

If we are sure that when options expire, Taiwan Index will be around 25,500. 

## Scenario 3

If we are sure that when options expire, Taiwan Index will be away from 25,500 but isn't sure which direction it will be. 

## Scenario 4

Are there any arbitrage opportunities?

# Results

For following scenarios, we denote the strike price of options as K.

## Scenario 1

Bull Spread
- Long Position: call option with strike price K1
- Short Position:  call option with strike price k2
- Limitation: K1<K2

### Profit

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/faa05df2-c7e1-41f0-8990-ba33dd2b8c01" />

## Scenario 2

Butterfly Spread
- Long Position: put option with strike price K1, put option with strike price K3
- Short Position:  2 put options with strike price k2
- Limitation: K1<K2<K3 , K2-K1 = K3-K2 , K2 is usually set to our expectation of future index level

Straddle
- Long Position: None
- Short Position: call option with strike price K1, put option with strike price K1
- Limitation: K1 is usually set to our expectation of future index level

### Profit

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/57e1eb91-2836-4eab-97e5-ae8f9671008a" />


## Scenario 3

Strangle
- Long Position: call option with strike price K1, put option with strike price K2
- Short Position:  None
- Limitation: K1>K2, we usually set the expectation of future index level that will be far away from as the midpoint between K1&K2 

Straddle
- Long Position: call option with strike price K1, put option with strike price K1
- Short Position: None
- Limitation: K1 is usually set to the expectation of future index level that will be far away from

### Profit

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/edcd36d0-3b87-4768-a59d-194c7f9e0857" />
<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/4d0f0d13-870f-4bf8-8099-691f7024b78b" />

## Scenario 4


- Long Position: call option with strike price K1, put option with strike price K2
- Short Position:  call option with strike price K2, put option with strike price K1
- Limitation: $K1\neqK2$

### Profit

Green line is the profit of combined 4 option contracts, which make a profit no matter what future index is.

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/cdee101d-3918-4f62-81cd-cdc3e3bb1e23" />


