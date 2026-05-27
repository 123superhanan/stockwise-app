## User Stories

- As a business owner, I want to scan receipts so inventory updates automatically
- As a business owner, I want low stock alerts so I never run out
- As a business owner, I want demand forecasts so I order correctly

## Functional Requirements

1. Receipt scanning with camera
2. Automatic product extraction
3. Inventory tracking
4. Low stock alerts
5. Demand forecasting
   EOF

cat > 02-api-endpoints.md << 'EOF'

# API Endpoints

## Receipts

- POST /api/receipts/upload - Upload and process receipt
- GET /api/receipts - List all receipts

## Products

- GET /api/products - Get inventory
- POST /api/products - Add product

## Sales

- POST /api/sales - Record sale

## Predictions

- GET /api/predictions/:product - Get demand forecast
  EOF

# Go back to root

cd ..
