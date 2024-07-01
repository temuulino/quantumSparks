# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.


[
  {
    "id": 174,
    "forms": [
      {
        "id": 193,
        "formFields": [
          {
            "id": 197,
            "fieldOptions": [
              {
                "id": 200,
                "name": "Female",
                "value": "female",
                "fieldId": 197,
                "createdAt": null,
                "updatedAt": null
              },
              {
                "id": 201,
                "name": "Male",
                "value": "male",
                "fieldId": 197,
                "createdAt": null,
                "updatedAt": null
              }
            ],
            "name": "gender",
            "type": "SELECT",
            "label": "gender",
            "placeholder": "select your gender ",
            "grid": null,
            "description": "gender",
            "title": "gender",
            "formId": 193,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 195,
            "fieldOptions": [],
            "name": "name",
            "type": "STRING",
            "label": "Name",
            "placeholder": "Name",
            "grid": null,
            "description": "mane",
            "title": "Name",
            "formId": 193,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 196,
            "fieldOptions": [],
            "name": "age",
            "type": "NUMBER",
            "label": "age",
            "placeholder": "Age",
            "grid": null,
            "description": "age",
            "title": "age",
            "formId": 193,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 198,
            "fieldOptions": [],
            "name": "birthdate",
            "type": "DATE",
            "label": "birthdate",
            "placeholder": "birthdate",
            "grid": null,
            "description": "birthdate",
            "title": "birthdate",
            "formId": 193,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 199,
            "fieldOptions": [],
            "name": "tesst",
            "type": "CHECKBOX",
            "label": "test",
            "placeholder": "test",
            "grid": null,
            "description": "test",
            "title": "test",
            "formId": 193,
            "createdAt": null,
            "updatedAt": null
          }
        ],
        "formValues": [
          {
            "id": 224,
            "formId": 193,
            "value": "{\"name\":\"121\"}",
            "createdAt": "2024-06-26T17:56:05.054322",
            "updatedAt": "2024-06-26T17:56:05.054322"
          },
          {
            "id": 226,
            "formId": 193,
            "value": "{\"name\":\"121\",\"age\":12,\"birthdate\":\"2024-06-25\",\"tesst\":[\"on\"]}",
            "createdAt": "2024-06-26T18:00:32.044707",
            "updatedAt": "2024-06-26T18:00:32.044707"
          }
        ],
        "name": "Харилцагч бүртгэх - MN ",
        "requestUrl": "\"Localhost/3000:\"fjdhfjkbaf",
        "requestMethod": "POST",
        "requestHeaders": "{hello}",
        "contentType": null,
        "groupId": 174,
        "createdAt": "2024-06-24T15:31:28.005418",
        "updatedAt": "2024-06-25T11:04:04.080089"
      },
      {
        "id": 212,
        "formFields": [],
        "formValues": [],
        "name": "Test-4",
        "requestUrl": "\"Localhost:3000\"",
        "requestMethod": "Post",
        "requestHeaders": "{hi}",
        "contentType": null,
        "groupId": 174,
        "createdAt": "2024-06-25T09:33:57.337755",
        "updatedAt": "2024-06-25T09:33:57.337755"
      },
      {
        "id": 213,
        "formFields": [],
        "formValues": [],
        "name": "Test-4",
        "requestUrl": "\"Localhost:3000\"",
        "requestMethod": "Post",
        "requestHeaders": "{hi}",
        "contentType": null,
        "groupId": 174,
        "createdAt": "2024-06-25T09:40:18.367436",
        "updatedAt": "2024-06-25T09:40:18.367436"
      }
    ],
    "name": "Бүртгэл-MN",
    "createdAt": "2024-06-21T15:27:48.073091",
    "updatedAt": "2024-06-27T11:14:51.035607"
  },
  {
    "id": 227,
    "forms": [
      {
        "id": 194,
        "formFields": [
          {
            "id": 202,
            "fieldOptions": [],
            "name": "name",
            "type": "STRING",
            "label": "Name",
            "placeholder": "name",
            "grid": null,
            "description": "Name",
            "title": "Name",
            "formId": 194,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 203,
            "fieldOptions": [],
            "name": "Age",
            "type": "NUMBER",
            "label": "Age",
            "placeholder": "age",
            "grid": null,
            "description": "age",
            "title": "age",
            "formId": 194,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 204,
            "fieldOptions": [],
            "name": "gender",
            "type": "SELECT",
            "label": "gender",
            "placeholder": "gender",
            "grid": null,
            "description": null,
            "title": "gender",
            "formId": 194,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 205,
            "fieldOptions": [],
            "name": "Address",
            "type": "STRING",
            "label": "address",
            "placeholder": "address",
            "grid": null,
            "description": null,
            "title": "address",
            "formId": 194,
            "createdAt": null,
            "updatedAt": null
          }
        ],
        "formValues": [
          {
            "id": 225,
            "formId": 194,
            "value": "{\"name\":\"121\",\"age\":12,\"birthdate\":\"2024-06-25\"}",
            "createdAt": "2024-06-26T18:00:24.610777",
            "updatedAt": "2024-07-01T15:15:11.746828"
          }
        ],
        "name": "Харилцагч бүртгэх - EN",
        "requestUrl": "\"Localhost:3000/dash\"",
        "requestMethod": "POST",
        "requestHeaders": "{hello}",
        "contentType": null,
        "groupId": 227,
        "createdAt": "2024-06-24T15:32:44.812331",
        "updatedAt": "2024-06-27T16:44:16.337311"
      },
      {
        "id": 211,
        "formFields": [],
        "formValues": [],
        "name": "test-4",
        "requestUrl": "\"Localhost:3000/teest\"",
        "requestMethod": "post",
        "requestHeaders": "{Hello}",
        "contentType": null,
        "groupId": 227,
        "createdAt": "2024-06-25T09:23:44.345436",
        "updatedAt": "2024-06-27T16:56:16.487212"
      }
    ],
    "name": "Бүртгэл-EN",
    "createdAt": "2024-06-27T11:15:12.021849",
    "updatedAt": "2024-06-27T11:15:12.021849"
  },
  {
    "id": 206,
    "forms": [
      {
        "id": 207,
        "formFields": [
          {
            "id": 208,
            "fieldOptions": [],
            "name": "Name",
            "type": "STRING",
            "label": "Name",
            "placeholder": "name",
            "grid": null,
            "description": null,
            "title": "Name",
            "formId": 207,
            "createdAt": null,
            "updatedAt": null
          },
          {
            "id": 209,
            "fieldOptions": [],
            "name": "Address",
            "type": "STRING",
            "label": "address",
            "placeholder": "Address",
            "grid": null,
            "description": null,
            "title": "Name",
            "formId": 207,
            "createdAt": null,
            "updatedAt": null
          }
        ],
        "formValues": [],
        "name": "зээлийн анкет",
        "requestUrl": "\"Localhost:3000/loan\"",
        "requestMethod": "POST",
        "requestHeaders": "{hollo}",
        "contentType": null,
        "groupId": 206,
        "createdAt": "2024-06-24T16:10:34.89438",
        "updatedAt": "2024-06-24T16:10:34.89438"
      },
      {
        "id": 210,
        "formFields": [],
        "formValues": [],
        "name": "test-4",
        "requestUrl": "\"localhost:3000/test\"",
        "requestMethod": "Post",
        "requestHeaders": "{hello}",
        "contentType": null,
        "groupId": 206,
        "createdAt": "2024-06-25T09:20:13.706784",
        "updatedAt": "2024-06-25T09:20:13.706784"
      }
    ],
    "name": "Зээл ",
    "createdAt": "2024-06-24T16:08:09.850882",
    "updatedAt": "2024-06-24T16:08:09.850882"
  }
]

