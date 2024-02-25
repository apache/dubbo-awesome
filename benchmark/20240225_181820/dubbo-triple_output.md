# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ops/ms
# Warmup Iteration   2: 9.770 ops/ms
# Warmup Iteration   3: 9.856 ops/ms
Iteration   1: 10.086 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.274 ±(99.9%) 3.282 ops/ms [Average]
  (min, avg, max) = (10.086, 10.274, 10.444), stdev = 0.180
  CI (99.9%): [6.992, 13.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ops/ms
# Warmup Iteration   2: 10.587 ops/ms
# Warmup Iteration   3: 10.597 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 11.041 ops/ms
Iteration   3: 11.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.982 ±(99.9%) 1.515 ops/ms [Average]
  (min, avg, max) = (10.887, 10.982, 11.041), stdev = 0.083
  CI (99.9%): [9.467, 12.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.892 ops/ms
# Warmup Iteration   2: 10.230 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.244 ops/ms
Iteration   3: 10.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.546 ±(99.9%) 4.774 ops/ms [Average]
  (min, avg, max) = (10.244, 10.546, 10.706), stdev = 0.262
  CI (99.9%): [5.772, 15.320] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.261 ops/ms
# Warmup Iteration   2: 8.563 ops/ms
# Warmup Iteration   3: 8.730 ops/ms
Iteration   1: 8.811 ops/ms
Iteration   2: 8.847 ops/ms
Iteration   3: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.807 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (8.763, 8.807, 8.847), stdev = 0.042
  CI (99.9%): [8.038, 9.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.072 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
Iteration   1: 3.090 ±(99.9%) 0.012 ms/op
Iteration   2: 3.089 ±(99.9%) 0.011 ms/op
Iteration   3: 2.985 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.055 ±(99.9%) 1.101 ms/op [Average]
  (min, avg, max) = (2.985, 3.055, 3.090), stdev = 0.060
  CI (99.9%): [1.954, 4.156] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.937 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.008 ms/op
Iteration   1: 2.938 ±(99.9%) 0.006 ms/op
Iteration   2: 2.897 ±(99.9%) 0.006 ms/op
Iteration   3: 2.877 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.904 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (2.877, 2.904, 2.938), stdev = 0.031
  CI (99.9%): [2.331, 3.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.927 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.011 ms/op
Iteration   1: 3.082 ±(99.9%) 0.011 ms/op
Iteration   2: 3.100 ±(99.9%) 0.009 ms/op
Iteration   3: 3.063 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.082 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (3.063, 3.082, 3.100), stdev = 0.018
  CI (99.9%): [2.746, 3.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.834 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.009 ms/op
Iteration   1: 3.659 ±(99.9%) 0.013 ms/op
Iteration   2: 3.635 ±(99.9%) 0.010 ms/op
Iteration   3: 3.678 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.657 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.635, 3.657, 3.678), stdev = 0.021
  CI (99.9%): [3.269, 4.046] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.553 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.014 ms/op
Iteration   1: 3.090 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.413 ms/op
                 createUser·p0.50:   2.888 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  12.986 ms/op
                 createUser·p0.9999: 17.323 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 3.138 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.381 ms/op
                 createUser·p0.50:   2.896 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  16.110 ms/op
                 createUser·p0.9999: 24.150 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.086 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.859 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   8.028 ms/op
                 createUser·p0.999:  15.021 ms/op
                 createUser·p0.9999: 24.630 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 308890
  mean =      3.105 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101860 
    [ 2.500,  5.000) = 189433 
    [ 5.000,  7.500) = 14130 
    [ 7.500, 10.000) = 2394 
    [10.000, 12.500) = 580 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     24.190 ms/op
     p(99.9990) =     25.737 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.908 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.011 ms/op
Iteration   1: 2.905 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.679 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  13.401 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 3.050 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.352 ms/op
                 existUser·p0.50:   2.757 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.882 ms/op
                 existUser·p0.999:  14.145 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 2.945 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.691 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   5.152 ms/op
                 existUser·p0.99:   7.422 ms/op
                 existUser·p0.999:  19.661 ms/op
                 existUser·p0.9999: 23.732 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 323396
  mean =      2.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127584 
    [ 2.500,  5.000) = 177697 
    [ 5.000,  7.500) = 14878 
    [ 7.500, 10.000) = 2437 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      2.707 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     14.454 ms/op
     p(99.9900) =     22.795 ms/op
     p(99.9990) =     28.315 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.282 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.013 ms/op
Iteration   1: 3.106 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.399 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  13.260 ms/op
                 getUser·p0.9999: 24.272 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.114 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.411 ms/op
                 getUser·p0.50:   2.867 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  17.739 ms/op
                 getUser·p0.9999: 21.979 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 3.077 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.372 ms/op
                 getUser·p0.50:   2.847 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  13.585 ms/op
                 getUser·p0.9999: 16.515 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 309487
  mean =      3.099 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103771 
    [ 2.500,  5.000) = 187015 
    [ 5.000,  7.500) = 15517 
    [ 7.500, 10.000) = 2402 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     14.459 ms/op
     p(99.9900) =     22.317 ms/op
     p(99.9990) =     24.662 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.016 ms/op
Iteration   1: 3.664 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.470 ms/op
                 listUser·p0.50:   3.355 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  14.178 ms/op
                 listUser·p0.9999: 26.568 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   2: 3.652 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.516 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   9.025 ms/op
                 listUser·p0.999:  14.679 ms/op
                 listUser·p0.9999: 17.449 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 3.686 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.406 ms/op
                 listUser·p0.50:   3.367 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   8.640 ms/op
                 listUser·p0.999:  18.423 ms/op
                 listUser·p0.9999: 25.163 ms/op
                 listUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261615
  mean =      3.668 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44792 
    [ 2.500,  5.000) = 182726 
    [ 5.000,  7.500) = 28614 
    [ 7.500, 10.000) = 4090 
    [10.000, 12.500) = 761 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     15.338 ms/op
     p(99.9900) =     24.931 ms/op
     p(99.9990) =     29.081 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.274 ± 3.282  ops/ms
ClientPb.existUser                       thrpt       3  10.982 ± 1.515  ops/ms
ClientPb.getUser                         thrpt       3  10.546 ± 4.774  ops/ms
ClientPb.listUser                        thrpt       3   8.807 ± 0.769  ops/ms
ClientPb.createUser                       avgt       3   3.055 ± 1.101   ms/op
ClientPb.existUser                        avgt       3   2.904 ± 0.573   ms/op
ClientPb.getUser                          avgt       3   3.082 ± 0.336   ms/op
ClientPb.listUser                         avgt       3   3.657 ± 0.388   ms/op
ClientPb.createUser                     sample  308890   3.105 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.381           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.057           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.190           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  323396   2.965 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.352           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.707           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.454           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.795           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.721           ms/op
ClientPb.getUser                        sample  309487   3.099 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.372           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.859           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.459           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.317           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  261615   3.668 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.406           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.359           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.259           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.338           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.931           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.064           ms/op
