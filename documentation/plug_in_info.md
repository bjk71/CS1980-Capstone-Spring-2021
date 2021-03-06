# Choosing a Github Plug-In

<h3>What are we choosing a plug-in for?</h3>

We would like a github plug-in to maintain an environment with continuous integration and development. More specifically, we would like a plug-in to automatically run our test cases upon a pull request.

<h3>Options</h3>

When looking to select a github plug-in for this project, we considered 3 options.

1. Semaphore <br/>

	Pros:
	 - Fastest CI/CD platform on the market.
	 - Easy setup.
	 - Free for private github repos.
	 - Highly functional with docker. <br/>
	 
	Cons:
	 - Uses a seperate application. <br/>
	 
	 ![Semaphore Image](https://marketplace-screenshots.githubusercontent.com/264/f1e7013c-46eb-11e7-82c1-1e0d83e4aea3?auto=webp&format=jpeg&width=670&dpr=1.5)
	 
2. Codefresh <br/>

	Pros:
	 - Tailor made for Docker.
	 - Can run integration tests in parallel. <br/>
	 
	Cons:
	 - Uses a seperate application.
	 - More difficult setup. <br/>
	 
	 ![Codefresh Image](https://marketplace-screenshots.githubusercontent.com/324/04430800-552a-11e9-9000-791039023c7d?auto=webp&format=jpeg&width=670&dpr=1.5)
	 
3. Check Run Reporter <br/>

	Pros:
	 - Works directly inside of github, modifies github ui.
	 - Runs tests for every pull request right in github.
	 - Does not use a seperate application. <br/>
	 
	Cons:
	 - Less features.
	 - Costs $5 a month for private repository use. <br/>
	 
	 ![Check Run Reporter Image](https://marketplace-screenshots.githubusercontent.com/4189/ffe8ad00-c513-11e9-93d3-97890328d5d4?auto=webp&format=jpeg&width=670&dpr=1.5)

<h3>Our Selection: Check Run Reporter</h3>

We decided to use the Check Run Reporter because it fits what we want to do perfectly in terms of working directly in github as well as running each of the tests at the pull request.

<h3>Link to plug-in</h3>
Here is the link to the download and description for Check Run-Reporter: https://github.com/marketplace/check-run-reporter.


