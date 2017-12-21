# params keyword benchmark
C# params keyword benchmark repository


``` ini

BenchmarkDotNet=v0.10.11, OS=macOS 10.13.1 (17B1003) [Darwin 17.2.0]
Processor=Intel Core i5-7360U CPU 2.30GHz (Kaby Lake), ProcessorCount=4
.NET Core SDK=2.0.3
  [Host]     : .NET Core 2.0.3 (Framework 4.6.0.0), 64bit RyuJIT
  DefaultJob : .NET Core 2.0.3 (Framework 4.6.0.0), 64bit RyuJIT


```
|  Method |      Mean |     Error |    StdDev |
|-------- |----------:|----------:|----------:|
| Classic |  31.52 ns | 0.5252 ns | 0.4385 ns |
|  Params | 102.40 ns | 2.2018 ns | 4.4977 ns |
