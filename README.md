Student Project done in 3rd year. <br>
Subject - Software Components (Softverske komponente)

Schedule Management Library
Overview

This Java library is designed for managing scheduling data with two distinct implementations, offering versatility in handling schedules in both time and space dimensions. It provides a unified API for schedule operations, adaptable for various use cases like academic schedules.
Features

    Flexible Schedule Representation: Supports schedules containing terms with linked data such as subject names, instructors, types of classes, and student groups.
    Customizable Term Data: Ability to attach arbitrary data to terms, providing extensibility.
    Space Representation: Includes data on capacity and equipment in spaces like classrooms.
    Operations: Includes initialization, adding/removing/moving terms, capacity handling, and more.
    Searching and Viewing: Features to check term availability, list free terms based on various criteria, and search schedules by linked data (e.g., instructor schedules).

Implementations
Collection of Terms

    Represents schedule as a collection of specific time-space terms.

Weekly Basis in a Given Period

    Groups terms as recurring events on a weekly basis for a specified period, including exceptions.

CLI Program

    A command-line program using the library to manage a real-world schedule, such as a university class schedule.

File Handling

    Functions to load and save schedules in various formats (JSON, CSV) with flexible configurations.

Getting Started

    [Instructions on how to set up and use the library, including code snippets]

Requirements

    Java [specific version]
    [Any other dependencies]

Installation

    Instructions on how to install and integrate the library into your Java project.

Contributing

    Guidelines on how to contribute to the library.

License

    Information about the project's license.
