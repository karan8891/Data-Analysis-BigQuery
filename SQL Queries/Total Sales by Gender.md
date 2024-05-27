
SELECT gender, SUM(price * quantity) AS total_sales_gender<br />
FROM `ncpl-420514.project1.customer_sales`<br />
GROUP BY gender;<br />
