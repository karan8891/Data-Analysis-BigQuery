
CREATE TABLE `ncpl-420514.project1.customer_sales_partitioned`<br />
PARTITION BY invoice_date<br />
CLUSTER BY gender<br />
AS<br />
SELECT * FROM `ncpl-420514.project1.customer_sales`;<br />
