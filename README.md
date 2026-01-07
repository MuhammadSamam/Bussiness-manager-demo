# Bussiness-manager-demo
Bussiness manager



  
  
  
  


  

    
Business Dealing App (Demo)

    
Inventory • Sales • Analytics


<div class="flex">
  <div class="stat">Total Products: <strong id="totalProducts">0</strong></div>
  <div class="stat">Total Stock: <strong id="totalStock">0</strong></div>
  <div class="stat">Total Sales (€): <strong id="totalSales">0</strong></div>
</div>

<div class="card">
  <h3>Add Product</h3>
  <input id="pname" placeholder="Product name" />
  <input id="pqty" type="number" placeholder="Quantity" />
  <input id="pprice" type="number" placeholder="Price" />
  <button onclick="addProduct()">Add</button>
</div>

<div class="card">
  <h3>Inventory</h3>
  <table>
    <thead>
      <tr><th>Product</th><th>Qty</th><th>Price</th><th>Sell</th></tr>
    </thead>
    <tbody id="inventory"></tbody>
  </table>
</div>

<div class="card">
  <h3>Sales History</h3>
  <table>
    <thead>
      <tr><th>Product</th><th>Qty</th><th>Total (€)</th><th>Date</th></tr>
    </thead>
    <tbody id="sales"></tbody>
  </table>
</div>


  




