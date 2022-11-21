# Lab 8 - Starter
1. I would fit my automated tests within a Github action that runs whenever code is pushed. This is so that before every push is deployed to production, the tests would run and check to see it the code is operational and works as intended.
2. No, for testing if a function returns the correct output, a unit test would be more appropiate becuase an E2E approach would test more than just that function we're interested in.
3. No, there are more than 1 components that would need to be tested for this feature: sending and recieving. It would get complicated because now we are working with two different components that need to interact with each other
4. Yes, this can be achieved by testing with random message inputs of variable length