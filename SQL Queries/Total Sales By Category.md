
SELECT category, SUM(price * quantity) AS total_sales_category<br />
FROM `ncpl-420514.project1.customer_sales`<br />
GROUP BY category;<br />
