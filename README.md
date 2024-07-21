# EBrief

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)
- [License](#license)

## Description

EBrief is a system for prosecutors to efficiently prepare for and conduct court lists. It enables prosecutors to download court files to their local machine prepare for upcoming court hearings, and to have rapid access to information about court files during court hearings.

EBrief was designed to address inefficiencies in the current system which was gated by poor network conditions.

The front end of the application is build with Blazor Web Assembly and styled with Tailwind CSS. Data is retrieved from the organisation's database and stored locally on the user's machine with Sqlite.

Court lists can be exported to a custom file type and shared with other users who can then import the file into their own instance of the application.

This repo provides a demonstration of the functionality of the application, but does not include the executable, nor a complete catalogue of features.

## Installation

Clone the repo to your local machine:

```bash
  git clone https://github.com/craigrobertsdev/Social-Network-API.git
```

<br>
You will need the [.NET 8 SDK installed](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
