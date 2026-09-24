# Purelane Shopify Storefront

A custom Purelane Shopify storefront implemented using the Shopify Dawn theme and Liquid.

## Storefront

Shopify Development Store:

https://purelane-assignment-sieyfptz.myshopify.com

## Tech Stack

- Shopify
- Shopify Liquid
- Dawn Theme
- HTML5
- CSS3
- JavaScript
- Shopify Products
- Shopify Cart
- Responsive Design

## Implemented Features

- Purelane custom homepage
- Custom navigation and header
- Hero section
- Shopify product grid
- Real Shopify product data
- Product images and pricing
- Sold-out product handling
- Product without image handling
- Long product title handling
- Add to Cart functionality
- Shopify cart functionality
- Best-selling combos section
- Bundle section
- Customer reviews rail
- Responsive mobile layout
- Custom Purelane footer

## Product Requirements

The storefront includes the required product variations:

- Regular product
- Sold-out product
- Product without an image
- Product with a deliberately long title

## Shopify Integration

The homepage product grid uses Shopify Liquid to retrieve products from the store.

Products can be added directly to the Shopify cart from the homepage.

The Shopify cart supports:

- Increasing quantity
- Decreasing quantity
- Removing products
- Updating cart totals

## Theme Structure

The implementation is based on the Shopify Dawn theme.

Important files include:

- `templates/index.json`
- `sections/purelane-original-homepage.liquid`
- `layout/theme.liquid`

The Purelane homepage is implemented using Shopify Liquid while preserving the supplied Purelane design and layout.

## Responsive Design

The storefront was checked using Shopify's mobile preview and supports responsive layouts for desktop and mobile screen sizes.

## Development Notes

The provided Purelane homepage HTML was integrated into the Shopify Dawn theme and adapted to work with Shopify Liquid and real Shopify product data.

The original visual design was preserved while adding Shopify-specific functionality such as product rendering and cart integration.

The Dawn theme's default header and footer were disabled where necessary to prevent duplication with the custom Purelane header and footer.

## AI Workflow

AI assistance was used during development for:

- Understanding Shopify theme structure
- Converting the supplied HTML into Shopify Liquid
- Debugging Liquid and theme issues
- Integrating Shopify product data
- Implementing Shopify cart functionality
- Troubleshooting responsive behavior
- Reviewing implementation details
- Debugging and resolving Shopify theme issues

All final implementation decisions, configuration, testing, and verification were performed in the Shopify development store.

## Testing

The storefront was tested for:

- Homepage rendering
- Product display
- Product pricing
- Product availability
- Add to cart
- Cart quantity increase
- Cart quantity decrease
- Cart item removal
- Mobile responsiveness
- Products with and without images
- Long product titles
- Sold-out product display

## Repository

GitHub:

https://github.com/SakshiHosale/purelane-shopify-theme