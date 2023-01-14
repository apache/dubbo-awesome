# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.010 ops/ms
# Warmup Iteration   2: 5.256 ops/ms
# Warmup Iteration   3: 8.395 ops/ms
Iteration   1: 8.986 ops/ms
Iteration   2: 9.250 ops/ms
Iteration   3: 9.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.229 ±(99.9%) 4.237 ops/ms [Average]
  (min, avg, max) = (8.986, 9.229, 9.449), stdev = 0.232
  CI (99.9%): [4.992, 13.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 9.028 ops/ms
# Warmup Iteration   3: 9.271 ops/ms
Iteration   1: 9.754 ops/ms
Iteration   2: 10.100 ops/ms
Iteration   3: 9.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.911 ±(99.9%) 3.201 ops/ms [Average]
  (min, avg, max) = (9.754, 9.911, 10.100), stdev = 0.175
  CI (99.9%): [6.710, 13.112] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.914 ops/ms
# Warmup Iteration   2: 8.762 ops/ms
# Warmup Iteration   3: 9.215 ops/ms
Iteration   1: 9.340 ops/ms
Iteration   2: 9.611 ops/ms
Iteration   3: 9.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.421 ±(99.9%) 3.020 ops/ms [Average]
  (min, avg, max) = (9.312, 9.421, 9.611), stdev = 0.166
  CI (99.9%): [6.401, 12.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.383 ops/ms
# Warmup Iteration   2: 6.833 ops/ms
# Warmup Iteration   3: 7.651 ops/ms
Iteration   1: 7.894 ops/ms
Iteration   2: 7.657 ops/ms
Iteration   3: 8.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.853 ±(99.9%) 3.265 ops/ms [Average]
  (min, avg, max) = (7.657, 7.853, 8.008), stdev = 0.179
  CI (99.9%): [4.588, 11.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.905 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.006 ms/op
Iteration   1: 3.397 ±(99.9%) 0.008 ms/op
Iteration   2: 3.492 ±(99.9%) 0.012 ms/op
Iteration   3: 3.287 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.392 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (3.287, 3.392, 3.492), stdev = 0.102
  CI (99.9%): [1.524, 5.260] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.228 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.004 ms/op
Iteration   1: 3.200 ±(99.9%) 0.013 ms/op
Iteration   2: 3.261 ±(99.9%) 0.006 ms/op
Iteration   3: 3.160 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.207 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.160, 3.207, 3.261), stdev = 0.051
  CI (99.9%): [2.278, 4.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.318 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.006 ms/op
Iteration   1: 3.402 ±(99.9%) 0.005 ms/op
Iteration   2: 3.369 ±(99.9%) 0.014 ms/op
Iteration   3: 3.466 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.413 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.369, 3.413, 3.466), stdev = 0.049
  CI (99.9%): [2.514, 4.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.006 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.007 ms/op
Iteration   1: 4.092 ±(99.9%) 0.006 ms/op
Iteration   2: 3.889 ±(99.9%) 0.013 ms/op
Iteration   3: 4.289 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.090 ±(99.9%) 3.648 ms/op [Average]
  (min, avg, max) = (3.889, 4.090, 4.289), stdev = 0.200
  CI (99.9%): [0.442, 7.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.097 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.014 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  21.726 ms/op
                 createUser·p0.9999: 25.399 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.526 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  23.630 ms/op
                 createUser·p0.9999: 26.968 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  21.099 ms/op
                 createUser·p0.9999: 32.272 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273575
  mean =      3.507 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8896 
    [ 2.500,  5.000) = 257240 
    [ 5.000,  7.500) = 6187 
    [ 7.500, 10.000) = 720 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     31.663 ms/op
     p(99.9990) =     34.882 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.900 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.010 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  20.427 ms/op
                 existUser·p0.9999: 24.572 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  11.604 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.294 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  21.254 ms/op
                 existUser·p0.9999: 30.878 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286303
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14020 
    [ 2.500,  5.000) = 267420 
    [ 5.000,  7.500) = 3566 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     11.611 ms/op
     p(99.9900) =     29.724 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.613 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.012 ms/op
Iteration   1: 3.456 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  22.493 ms/op
                 getUser·p0.9999: 28.580 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  23.452 ms/op
                 getUser·p0.9999: 26.524 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.572 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.325 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  19.704 ms/op
                 getUser·p0.9999: 25.629 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277684
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5104 
    [ 2.500,  5.000) = 265974 
    [ 5.000,  7.500) = 5259 
    [ 7.500, 10.000) = 903 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 102 

  Percentiles, ms/op:
      p(0.0000) =      0.325 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     21.965 ms/op
     p(99.9900) =     27.303 ms/op
     p(99.9990) =     28.978 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.558 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.014 ms/op
Iteration   1: 4.083 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  22.272 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 3.938 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.891 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  14.953 ms/op
                 listUser·p0.9999: 16.880 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241779
  mean =      3.969 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 235065 
    [ 5.000,  7.500) = 5247 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.629 ms/op
     p(99.9000) =     16.437 ms/op
     p(99.9900) =     23.942 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.229 ± 4.237  ops/ms
ClientPb.existUser                       thrpt       3   9.911 ± 3.201  ops/ms
ClientPb.getUser                         thrpt       3   9.421 ± 3.020  ops/ms
ClientPb.listUser                        thrpt       3   7.853 ± 3.265  ops/ms
ClientPb.createUser                       avgt       3   3.392 ± 1.868   ms/op
ClientPb.existUser                        avgt       3   3.207 ± 0.929   ms/op
ClientPb.getUser                          avgt       3   3.413 ± 0.898   ms/op
ClientPb.listUser                         avgt       3   4.090 ± 3.648   ms/op
ClientPb.createUser                     sample  273575   3.507 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.364           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.997           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.299           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.663           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  286303   3.347 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.460           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.611           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.724           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523           ms/op
ClientPb.getUser                        sample  277684   3.456 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.325           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.965           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.303           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  241779   3.969 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.898           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.629           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.942           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
