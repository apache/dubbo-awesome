# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.088 ops/ms
# Warmup Iteration   2: 2.431 ops/ms
# Warmup Iteration   3: 4.831 ops/ms
Iteration   1: 5.246 ops/ms
Iteration   2: 5.408 ops/ms
Iteration   3: 5.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.407 ±(99.9%) 2.918 ops/ms [Average]
  (min, avg, max) = (5.246, 5.407, 5.566), stdev = 0.160
  CI (99.9%): [2.489, 8.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.802 ops/ms
# Warmup Iteration   2: 5.067 ops/ms
# Warmup Iteration   3: 5.924 ops/ms
Iteration   1: 5.952 ops/ms
Iteration   2: 6.060 ops/ms
Iteration   3: 6.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.023 ±(99.9%) 1.125 ops/ms [Average]
  (min, avg, max) = (5.952, 6.023, 6.060), stdev = 0.062
  CI (99.9%): [4.898, 7.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.589 ops/ms
# Warmup Iteration   2: 4.396 ops/ms
# Warmup Iteration   3: 5.686 ops/ms
Iteration   1: 5.792 ops/ms
Iteration   2: 5.833 ops/ms
Iteration   3: 5.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.815 ±(99.9%) 0.376 ops/ms [Average]
  (min, avg, max) = (5.792, 5.815, 5.833), stdev = 0.021
  CI (99.9%): [5.439, 6.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.482 ops/ms
# Warmup Iteration   2: 4.150 ops/ms
# Warmup Iteration   3: 4.802 ops/ms
Iteration   1: 4.796 ops/ms
Iteration   2: 4.639 ops/ms
Iteration   3: 4.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.768 ±(99.9%) 2.149 ops/ms [Average]
  (min, avg, max) = (4.639, 4.768, 4.870), stdev = 0.118
  CI (99.9%): [2.619, 6.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.535 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.381 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.825 ±(99.9%) 0.014 ms/op
Iteration   1: 6.005 ±(99.9%) 0.010 ms/op
Iteration   2: 5.547 ±(99.9%) 0.015 ms/op
Iteration   3: 5.626 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.726 ±(99.9%) 4.465 ms/op [Average]
  (min, avg, max) = (5.547, 5.726, 6.005), stdev = 0.245
  CI (99.9%): [1.261, 10.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.782 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.447 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.522 ±(99.9%) 0.008 ms/op
Iteration   1: 5.050 ±(99.9%) 0.012 ms/op
Iteration   2: 5.251 ±(99.9%) 0.006 ms/op
Iteration   3: 5.279 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.193 ±(99.9%) 2.280 ms/op [Average]
  (min, avg, max) = (5.050, 5.193, 5.279), stdev = 0.125
  CI (99.9%): [2.914, 7.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.877 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.503 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.691 ±(99.9%) 0.006 ms/op
Iteration   1: 5.852 ±(99.9%) 0.006 ms/op
Iteration   2: 5.640 ±(99.9%) 0.008 ms/op
Iteration   3: 5.467 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.653 ±(99.9%) 3.517 ms/op [Average]
  (min, avg, max) = (5.467, 5.653, 5.852), stdev = 0.193
  CI (99.9%): [2.135, 9.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.356 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.462 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.555 ±(99.9%) 0.012 ms/op
Iteration   1: 6.738 ±(99.9%) 0.011 ms/op
Iteration   2: 6.636 ±(99.9%) 0.015 ms/op
Iteration   3: 6.496 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.623 ±(99.9%) 2.215 ms/op [Average]
  (min, avg, max) = (6.496, 6.623, 6.738), stdev = 0.121
  CI (99.9%): [4.408, 8.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.594 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.823 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.150 ±(99.9%) 0.028 ms/op
Iteration   1: 5.656 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.587 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   8.020 ms/op
                 createUser·p0.99:   10.710 ms/op
                 createUser·p0.999:  28.047 ms/op
                 createUser·p0.9999: 32.468 ms/op
                 createUser·p1.00:   33.292 ms/op

Iteration   2: 5.565 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.619 ms/op
                 createUser·p0.95:   7.296 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  27.237 ms/op
                 createUser·p0.9999: 33.063 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   3: 5.661 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.905 ms/op
                 createUser·p0.99:   10.961 ms/op
                 createUser·p0.999:  27.951 ms/op
                 createUser·p0.9999: 32.995 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170493
  mean =      5.627 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 53150 
    [ 5.000,  7.500) = 107591 
    [ 7.500, 10.000) = 7385 
    [10.000, 12.500) = 1552 
    [12.500, 15.000) = 410 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     27.804 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     33.986 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.945 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 6.326 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.419 ±(99.9%) 0.019 ms/op
Iteration   1: 5.397 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.572 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   10.212 ms/op
                 existUser·p0.999:  21.758 ms/op
                 existUser·p0.9999: 26.339 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   2: 5.377 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   10.454 ms/op
                 existUser·p0.999:  15.699 ms/op
                 existUser·p0.9999: 27.822 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 5.344 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.359 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.225 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  24.977 ms/op
                 existUser·p0.9999: 35.521 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178441
  mean =      5.373 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 76934 
    [ 5.000,  7.500) = 93514 
    [ 7.500, 10.000) = 5692 
    [10.000, 12.500) = 1441 
    [12.500, 15.000) = 493 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     20.164 ms/op
     p(99.9900) =     33.111 ms/op
     p(99.9990) =     36.106 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.185 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.582 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.744 ±(99.9%) 0.022 ms/op
Iteration   1: 5.397 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.447 ms/op
                 getUser·p0.95:   7.881 ms/op
                 getUser·p0.99:   11.387 ms/op
                 getUser·p0.999:  24.208 ms/op
                 getUser·p0.9999: 28.087 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   2: 5.576 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   8.151 ms/op
                 getUser·p0.99:   11.436 ms/op
                 getUser·p0.999:  27.308 ms/op
                 getUser·p0.9999: 30.841 ms/op
                 getUser·p1.00:   35.783 ms/op

Iteration   3: 5.472 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.286 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.373 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  27.246 ms/op
                 getUser·p0.9999: 30.725 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175073
  mean =      5.481 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 68591 
    [ 5.000,  7.500) = 96845 
    [ 7.500, 10.000) = 6842 
    [10.000, 12.500) = 1831 
    [12.500, 15.000) = 528 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     25.035 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     34.159 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.520 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 8.145 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.837 ±(99.9%) 0.028 ms/op
Iteration   1: 6.535 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  28.674 ms/op
                 listUser·p0.9999: 31.333 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 6.368 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.921 ms/op
                 listUser·p0.999:  28.499 ms/op
                 listUser·p0.9999: 32.533 ms/op
                 listUser·p1.00:   34.472 ms/op

Iteration   3: 6.636 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   6.382 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  22.807 ms/op
                 listUser·p0.9999: 30.644 ms/op
                 listUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147356
  mean =      6.511 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 3958 
    [ 5.000,  7.500) = 126142 
    [ 7.500, 10.000) = 13218 
    [10.000, 12.500) = 2807 
    [12.500, 15.000) = 557 
    [15.000, 17.500) = 304 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      6.210 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     27.886 ms/op
     p(99.9900) =     31.426 ms/op
     p(99.9990) =     33.991 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.407 ± 2.918  ops/ms
ClientPb.existUser                       thrpt       3   6.023 ± 1.125  ops/ms
ClientPb.getUser                         thrpt       3   5.815 ± 0.376  ops/ms
ClientPb.listUser                        thrpt       3   4.768 ± 2.149  ops/ms
ClientPb.createUser                       avgt       3   5.726 ± 4.465   ms/op
ClientPb.existUser                        avgt       3   5.193 ± 2.280   ms/op
ClientPb.getUser                          avgt       3   5.653 ± 3.517   ms/op
ClientPb.listUser                         avgt       3   6.623 ± 2.215   ms/op
ClientPb.createUser                     sample  170493   5.627 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.587           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.750           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.699           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.804           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.030           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  178441   5.373 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.444           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.299           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.551           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.164           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.111           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  175073   5.481 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.684           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.035           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.605           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  147356   6.511 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.210           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.886           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.426           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.472           ms/op
