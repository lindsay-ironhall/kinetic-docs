# Health Factor

## Your Health Factor

To manage risks effectively, Kinetic advises users to monitor their loan's health factors closely. Borrowers should be proactive in managing their positions and consider repaying or depositing additional assets if their health factor declines. Staying informed about blockchain developments and the assets used as collateral can help users make informed decisions.

### How Health Factor is Calculated

The **Health Factor (HF)** measures how safe a user's borrowed funds are compared to their supplied collateral. The formula is:

<figure><img src="../.gitbook/assets/Screenshot 2025-03-24 104249.png" alt=""><figcaption></figcaption></figure>

**Important:** Each asset has a **Collateral Factor**, meaning only a percentage of its value counts toward your borrowing power.

**Example Calculation:**

* **Collateral Factor:**
  * sFLR: **70%**
  * USDC: **80%**
* **User Supplied Assets:**
  * sFLR: **$2,000**
  * USDC: **$1,500**
  * **Total Collateral:** **$3,500**
* **Borrow Limit Calculation:**

<div align="center" data-full-width="false"><figure><img src="../.gitbook/assets/Screenshot 2025-03-24 104530.png" alt="" width="375"><figcaption></figcaption></figure></div>

* **User’s Actual Borrow: $1,500**
*   **Health Factor Calculation:**



<figure><img src="../.gitbook/assets/Screenshot 2025-03-24 104704.png" alt="" width="113"><figcaption></figcaption></figure>

If a user's **Health Factor drops to 1**, they risk **liquidation**. In this example, that happens when their borrow amount reaches **$2,600**.

<br>
