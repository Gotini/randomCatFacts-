//GitHum API Library
const { Octokit } = require('@octokit/rest');

//Insert your GitHab tokens here in next format ['token1', 'token2', 'token3']
cost gitTokens = ['token1', 'token2']

//Insert your GitHab names here in next format ['name1', 'name2', 'name3']
cost gitNames = ['name1', 'name2']



//Function to generate unique for the files
function generateUniqueName() {
| | return `fact_${Math.floor(Math.random() * 150000000)}.txt`;
}


//Function to push rondom cat fact to the GitHub repo
async function pushRandomCatName(repoOwner, token) {
| | //API initialization
| | conts octokit = new Octokit({ auth: token });
| |
| |
| |
| |
| |
| |
| |
| |

# randomCatFacts-
