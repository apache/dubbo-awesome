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
# Warmup Iteration   1: 2.064 ops/ms
# Warmup Iteration   2: 4.996 ops/ms
# Warmup Iteration   3: 8.362 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 9.390 ops/ms
Iteration   3: 9.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.057 ±(99.9%) 7.692 ops/ms [Average]
  (min, avg, max) = (8.583, 9.057, 9.390), stdev = 0.422
  CI (99.9%): [1.365, 16.749] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.669 ops/ms
# Warmup Iteration   2: 8.513 ops/ms
# Warmup Iteration   3: 9.581 ops/ms
Iteration   1: 9.178 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.434 ±(99.9%) 4.801 ops/ms [Average]
  (min, avg, max) = (9.178, 9.434, 9.703), stdev = 0.263
  CI (99.9%): [4.633, 14.235] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.686 ops/ms
# Warmup Iteration   2: 8.258 ops/ms
# Warmup Iteration   3: 9.230 ops/ms
Iteration   1: 9.327 ops/ms
Iteration   2: 9.105 ops/ms
Iteration   3: 9.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.304 ±(99.9%) 3.432 ops/ms [Average]
  (min, avg, max) = (9.105, 9.304, 9.480), stdev = 0.188
  CI (99.9%): [5.872, 12.736] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.600 ops/ms
# Warmup Iteration   2: 7.187 ops/ms
# Warmup Iteration   3: 7.436 ops/ms
Iteration   1: 8.128 ops/ms
Iteration   2: 7.644 ops/ms
Iteration   3: 7.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.875 ±(99.9%) 4.431 ops/ms [Average]
  (min, avg, max) = (7.644, 7.875, 8.128), stdev = 0.243
  CI (99.9%): [3.444, 12.306] (assumes normal distribution)


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
# Warmup Iteration   1: 11.534 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.004 ms/op
Iteration   1: 3.616 ±(99.9%) 0.005 ms/op
Iteration   2: 3.443 ±(99.9%) 0.005 ms/op
Iteration   3: 3.575 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.544 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (3.443, 3.544, 3.616), stdev = 0.091
  CI (99.9%): [1.891, 5.198] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.714 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.009 ms/op
Iteration   1: 3.307 ±(99.9%) 0.003 ms/op
Iteration   2: 3.323 ±(99.9%) 0.004 ms/op
Iteration   3: 3.321 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.307, 3.317, 3.323), stdev = 0.009
  CI (99.9%): [3.157, 3.477] (assumes normal distribution)


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
# Warmup Iteration   1: 9.785 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.004 ms/op
Iteration   1: 3.449 ±(99.9%) 0.006 ms/op
Iteration   2: 3.486 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.457 ±(99.9%) 0.474 ms/op [Average]
  (min, avg, max) = (3.436, 3.457, 3.486), stdev = 0.026
  CI (99.9%): [2.983, 3.931] (assumes normal distribution)


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
# Warmup Iteration   1: 10.395 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.010 ms/op
Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
Iteration   3: 4.043 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.997 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.971, 3.997, 4.043), stdev = 0.040
  CI (99.9%): [3.275, 4.719] (assumes normal distribution)


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
# Warmup Iteration   1: 10.086 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
Iteration   1: 3.730 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  13.619 ms/op
                 createUser·p0.9999: 30.623 ms/op
                 createUser·p1.00:   31.425 ms/op

Iteration   2: 3.418 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.730 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 35.628 ms/op
                 createUser·p1.00:   37.356 ms/op

Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  21.165 ms/op
                 createUser·p0.9999: 28.731 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271491
  mean =      3.536 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4232 
    [ 2.500,  5.000) = 255334 
    [ 5.000,  7.500) = 10058 
    [ 7.500, 10.000) = 1271 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     37.196 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.329 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
Iteration   1: 3.358 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  11.649 ms/op
                 existUser·p0.9999: 22.853 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  22.564 ms/op
                 existUser·p0.9999: 29.222 ms/op
                 existUser·p1.00:   30.245 ms/op

Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  22.933 ms/op
                 existUser·p0.9999: 28.592 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283412
  mean =      3.386 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5387 
    [ 2.500,  5.000) = 271310 
    [ 5.000,  7.500) = 5738 
    [ 7.500, 10.000) = 625 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     28.726 ms/op
     p(99.9990) =     29.841 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 10.520 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.013 ms/op
Iteration   1: 3.581 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 23.241 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  21.788 ms/op
                 getUser·p0.9999: 25.634 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.635 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  19.792 ms/op
                 getUser·p0.9999: 30.415 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270950
  mean =      3.542 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3954 
    [ 2.500,  5.000) = 257726 
    [ 5.000,  7.500) = 7958 
    [ 7.500, 10.000) = 854 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     30.723 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 11.403 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.014 ms/op
Iteration   1: 4.097 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  21.720 ms/op
                 listUser·p0.9999: 28.017 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   2: 4.026 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 17.959 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.114 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.190 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235334
  mean =      4.079 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 228241 
    [ 5.000,  7.500) = 4889 
    [ 7.500, 10.000) = 1315 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     26.131 ms/op
     p(99.9990) =     28.890 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.057 ± 7.692  ops/ms
ClientPb.existUser                       thrpt       3   9.434 ± 4.801  ops/ms
ClientPb.getUser                         thrpt       3   9.304 ± 3.432  ops/ms
ClientPb.listUser                        thrpt       3   7.875 ± 4.431  ops/ms
ClientPb.createUser                       avgt       3   3.544 ± 1.653   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 0.160   ms/op
ClientPb.getUser                          avgt       3   3.457 ± 0.474   ms/op
ClientPb.listUser                         avgt       3   3.997 ± 0.722   ms/op
ClientPb.createUser                     sample  271491   3.536 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.930           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.611           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.669           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  283412   3.386 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.395           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.534           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.726           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.245           ms/op
ClientPb.getUser                        sample  270950   3.542 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.938           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.906           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.426           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  235334   4.079 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.610           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.131           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.458           ms/op
