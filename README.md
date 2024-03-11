# TPP--Technological Peer Pressure
TPP measure in Cao, Ma, Tucker, and Wan (2018), 'Technological Peer Pressure and Product Disclosure', The Accounting Review, Vol 93 (6), pp 95-126.

# Variable Definition
$$TPP = log(f+\frac{\sum_{j \ne i}\omega_{ij}\times G_{j,t}}{G_{j,t}})$$ where $j$ represents firm $i$’s rival (any firm that overlaps 
with firm $i$ in the product markets), $t$ represents the fiscal year, $G$ is a firm’s R$&$D
stock, and $\omega_{ij}$ is the closeness weight. Specifically, $G$ is a firm’s cumulative R$&$D
investments in preceding years with the value of investments decaying by 15\% as each
year passes, i.e., $G_t = R&D_t + (1-15\%)G_{t-1}$, where $R&D_t$ is the firm’s R\&D expenses
in year $t$. $\omega_{ij}$ captures the spatial distance in the product markets between firms $i$ and
$j$ using industry segment sales: $\omega_{ij}=cos(\theta_{ij})=\frac{V_i}{||V_i||}\dot \frac{V_j}{||V_j||}\$, where ܸ$V_i$ is the vector of firm $i$’s sales with the $k_{th}$
element being the share of firm  $i$’s total sales in the preceding two years made in
industry (4-digit SIC) $k$. A higher value of TPP indicates more intense competition
faced by the sample firm. 
