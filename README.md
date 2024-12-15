# Next.js 15 Metadata Route Caching Issue

This repository demonstrates a caching issue encountered when using the `next/server` MetadataRoute in Next.js 15.  Despite setting appropriate `Cache-Control` headers, the expected caching behavior is not observed.

## Problem

The provided `metadata.js` file attempts to set a `Cache-Control` header to enable caching. However, the cache invalidation doesn't work as expected in the browser.

## Solution

The `metadataSolution.js` file offers a workaround, using the experimental API or providing a complete solution depending on what's feasible with Next.js API capabilities.