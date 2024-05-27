
SELECT category, SUM(price * quantity) AS total_sales_category
FROM `ncpl-420514.project1.customer_sales`
GROUP BY category;
