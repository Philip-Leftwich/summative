# data_cleaning

## The data
The fruitfly dataset Partridge and Farquhar (1981). From our understanding of sexual selection and reproductive biology in fruit flies, we know there is a well established 'cost' to reproduction in terms of reduced longevity for female fruitflies. The data from this experiment is designed to test whether increased sexual activity affects the lifespan of male fruitflies.

The flies used were an outbred stock, sexual activity was manipulated by supplying males with either new virgin females each day, previously mated females ( Inseminated, so remating rates are lower), or provide no females at all (Control). All groups were otherwise treated identically.

## variables
- type: type of female companion (virgin, inseminated, control(partners = 0))

- longevity: lifespan in days

- thorax: length of thorax in micrometres (a proxy for body size)

- sleep: percentage of the day spent sleeping

## Assignment
This dataset has non-standardised text, missing values and outliers - the aim of this repository is to produce an error checking and data cleaning script.
