# BlobTrigger - C<span>#</span>

The `BlobTrigger` makes it incredibly easy to react to new Blobs inside of Azure Blob Storage. This sample demonstrates a simple use case of processing data from a given Blob using C#.

## How it works

For a `BlobTrigger` to work, you provide a path which dictates where the blobs are located inside your container, and can also help restrict the types of blobs you wish to return. For instance, you can set the path to `samples/{name}.png` to restrict the trigger to only the samples path and only blobs with ".png" at the end of their name.

## Todo 

Update from `.Net Core2.2 to 3.1` (or later), and use the new attribute-syntax using the `Microsoft.Azure.WebJobs` namespace.