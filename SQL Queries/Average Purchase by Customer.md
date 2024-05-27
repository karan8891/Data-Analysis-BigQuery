
SELECT customer_id, AVG(price * quantity) AS avg_purchase_amt<br />
FROM `ncpl-420514.project1.customer_sales`<br />
GROUP BY customer_id;<br />
