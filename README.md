# Clean_Energy_project 


# Clear Energy 3-App Take-Home

## Overview

This project contains three React Native apps:

- Customer App
- Driver App
- Admin Mobile App

All three apps share the same API client, TypeScript types, and reusable components.



## Project Structure

```
apps/
  customer/
  driver/
  admin-mobile/

packages/
  shared/
    api/
    components/
    types/
    utils/
```

## Setup

Install dependencies:

```bash
npm install
```

Run mock API:

```bash
npx json-server mock-api.json --port 4000
```

Start the apps:

```bash
npm run customer
npm run driver
npm run admin
```

## Features

- Shared API client
- Shared OrderCard component
- Shared TypeScript types
- Loading, Empty, Error, and Success states
- Unit test for currency formatting






