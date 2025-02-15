# React Router Dom v6 Catch All Route Issue

This repository demonstrates a common issue encountered when using the catch-all route (`/*`) in React Router Dom v6. The catch-all route unintentionally matches all paths, preventing other routes from working as expected.  The solution demonstrates how to correctly use the catch-all route to handle only unmatched paths.

## Problem

The problem is in the order of the routes. The `/*` catch all route is defined before the other routes causing it to always match regardless of other specific routes.