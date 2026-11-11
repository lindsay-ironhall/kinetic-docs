# Protocol Parameters

**Collateral Factor**: This parameter plays a crucial role in determining the borrowing capacity against deposited assets. For example, a 60% Collateral Factor means that users can borrow up to 60% of the deposited asset's value.

**Reserve Factor**: The Reserve Factor is instrumental in safeguarding asset supply against potential borrower defaults and liquidation issues by allocating a portion of the interest earned to an asset's Reserve Pool. Analytical modeling determines the optimal range for this factor, typically falling between 5% to 30%. For instance, a 20% Reserve Factor implies that 20% of the interest paid by borrowers is channeled into the Reserve Pool. This mechanism enhances the protocol's stability and resilience over time.

**Borrow Cap**: This parameter sets the upper limit for borrowing a specific asset at any given time. For instance, a 2,000,000 Borrow Cap on FLR restricts the maximum amount of FLR that borrowers can access simultaneously and collectively on Kinetic. Such caps prevent excessive borrowing, maintain market equilibrium, and mitigate systemic risks within the lending protocol.

**Close Factor**: The Close Factor determines the maximum percentage of a borrower's outstanding debt that can be repaid in a single transaction during liquidation events. For example, a 50% Close Factor would allow liquidating up to 50% of the borrower's collateral if their health factor drops below 1. This conservative approach ensures prudent risk management and safeguards the protocol's liquidity during market downturns.

**Interest Rate Model**: Kinetic employs the Jump Rate Interest Model, a dynamic mechanism that adjusts interest rates based on asset utilization within the protocol. As asset utilization increases, signaling higher demand, interest rates experience significant jumps to incentivize asset deposits and loan repayments. For instance, when asset utilization reaches 80%, a substantial increase in interest rates occurs, stimulating user participation and maintaining liquidity within the lending ecosystem.
