<div id="cart-icon" onclick="toggleCart()">
    <span>🛒</span>
    <span id="cart-count">0</span>
</div>

<div id="cart-modal" class="modal">
    <div class="modal-content">
        <span class="close" onclick="toggleCart()">&times;</span>
        <h2>Your Order</h2>
        <hr>
        <div id="cart-items">
            <p>Your basket is empty.</p>
        </div>
        <div class="cart-footer">
            <div class="total-line">
                <strong>Total:</strong>
                <span id="cart-total">$0.00</span>
            </div>
            <button class="btn checkout-btn" onclick="checkout()">Checkout</button>
        </div>
    </div>
</div>
