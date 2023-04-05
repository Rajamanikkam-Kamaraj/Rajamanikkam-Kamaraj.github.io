<html>
  <head>
    <title>My CV</title>
  </head>
  <body>
    <h1>Rajamanikkam Kamaraj</h1>
    <p>Email: kamarajr@faf.cuni.cz</p>
    <h2>Education</h2>
    <ul>
      <li>M.Tech, Kalasalingam University, 2015-2017</li>
      <li>Ph.D, Charles University, 2022-present</li>
    </ul>
    <h2>Experience</h2>
    <ul>
      <li>Research Associate, Aragen Life Sciences (GVK Bio), 2020-2021</li>
      <li>Research Fellow, Dr. Reddy’s Institute of Life Sciences (DRILS), 2018-2020</li>
    </ul>
    <h2>Skills</h2>
    <ul>
      <li>Skill 1</li>
      <li>Skill 2</li>
    </ul>
  </body>
</html>

# Clone 5-HT2C receptor cDNA into a mammalian expression vector
from Bio import SeqIO

cDNA = SeqIO.read("5-HT2C_cDNA.fasta", "fasta")
expression_vector = "pcDNA3.1"

def clone(cDNA, expression_vector):
    # code to clone cDNA into expression vector
    pass

cloned_vector = clone(cDNA, expression_vector)

# Analyze screening results to identify potential drug candidates
import scipy.stats as stats

def analyze_data(screening_results):
    # code to analyze screening results and identify leads
    pass

# Load the screening results
screening_results = pd.read_csv("screening_results.csv")

# Analyze the data and print the p-value
p_value = analyze_data(screening_results)
print(f"p-value: {p_value}")

