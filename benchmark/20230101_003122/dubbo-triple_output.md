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
# Warmup Iteration   1: 0.986 ops/ms
# Warmup Iteration   2: 2.127 ops/ms
# Warmup Iteration   3: 4.581 ops/ms
Iteration   1: 4.993 ops/ms
Iteration   2: 5.135 ops/ms
Iteration   3: 5.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.122 ±(99.9%) 2.238 ops/ms [Average]
  (min, avg, max) = (4.993, 5.122, 5.237), stdev = 0.123
  CI (99.9%): [2.883, 7.360] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.431 ops/ms
# Warmup Iteration   2: 4.577 ops/ms
# Warmup Iteration   3: 5.577 ops/ms
Iteration   1: 5.569 ops/ms
Iteration   2: 5.653 ops/ms
Iteration   3: 5.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.606 ±(99.9%) 0.784 ops/ms [Average]
  (min, avg, max) = (5.569, 5.606, 5.653), stdev = 0.043
  CI (99.9%): [4.822, 6.390] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.194 ops/ms
# Warmup Iteration   2: 3.748 ops/ms
# Warmup Iteration   3: 5.326 ops/ms
Iteration   1: 5.546 ops/ms
Iteration   2: 5.225 ops/ms
Iteration   3: 5.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.430 ±(99.9%) 3.243 ops/ms [Average]
  (min, avg, max) = (5.225, 5.430, 5.546), stdev = 0.178
  CI (99.9%): [2.187, 8.673] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.237 ops/ms
# Warmup Iteration   2: 3.516 ops/ms
# Warmup Iteration   3: 4.537 ops/ms
Iteration   1: 4.498 ops/ms
Iteration   2: 4.683 ops/ms
Iteration   3: 4.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.588 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (4.498, 4.588, 4.683), stdev = 0.093
  CI (99.9%): [2.893, 6.283] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.063 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 7.290 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.035 ±(99.9%) 0.016 ms/op
Iteration   1: 5.999 ±(99.9%) 0.010 ms/op
Iteration   2: 5.886 ±(99.9%) 0.012 ms/op
Iteration   3: 5.902 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.929 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (5.886, 5.929, 5.999), stdev = 0.061
  CI (99.9%): [4.812, 7.046] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.406 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 7.521 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.731 ±(99.9%) 0.014 ms/op
Iteration   1: 5.726 ±(99.9%) 0.008 ms/op
Iteration   2: 5.611 ±(99.9%) 0.010 ms/op
Iteration   3: 5.651 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.663 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (5.611, 5.663, 5.726), stdev = 0.058
  CI (99.9%): [4.599, 6.727] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 18.814 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 7.568 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.088 ±(99.9%) 0.013 ms/op
Iteration   1: 6.104 ±(99.9%) 0.012 ms/op
Iteration   2: 6.225 ±(99.9%) 0.011 ms/op
Iteration   3: 6.093 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.141 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (6.093, 6.141, 6.225), stdev = 0.073
  CI (99.9%): [4.811, 7.471] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 23.787 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 9.484 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 7.103 ±(99.9%) 0.020 ms/op
Iteration   1: 7.013 ±(99.9%) 0.013 ms/op
Iteration   2: 7.040 ±(99.9%) 0.021 ms/op
Iteration   3: 7.079 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.044 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (7.013, 7.044, 7.079), stdev = 0.033
  CI (99.9%): [6.444, 7.644] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 21.256 ±(99.9%) 0.423 ms/op
# Warmup Iteration   2: 8.197 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.724 ±(99.9%) 0.039 ms/op
Iteration   1: 6.038 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.946 ms/op
                 createUser·p0.95:   9.513 ms/op
                 createUser·p0.99:   12.632 ms/op
                 createUser·p0.999:  19.761 ms/op
                 createUser·p0.9999: 29.158 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   2: 5.727 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.135 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  31.278 ms/op
                 createUser·p0.9999: 36.006 ms/op
                 createUser·p1.00:   37.421 ms/op

Iteration   3: 6.029 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   7.832 ms/op
                 createUser·p0.95:   8.995 ms/op
                 createUser·p0.99:   12.108 ms/op
                 createUser·p0.999:  30.670 ms/op
                 createUser·p0.9999: 32.958 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161902
  mean =      5.928 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 35243 
    [ 5.000,  7.500) = 109157 
    [ 7.500, 10.000) = 12868 
    [10.000, 12.500) = 3280 
    [12.500, 15.000) = 768 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 38 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.880 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     26.624 ms/op
     p(99.9900) =     35.115 ms/op
     p(99.9990) =     37.340 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.214 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 7.272 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.931 ±(99.9%) 0.025 ms/op
Iteration   1: 5.831 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   5.390 ms/op
                 existUser·p0.90:   7.594 ms/op
                 existUser·p0.95:   8.897 ms/op
                 existUser·p0.99:   11.862 ms/op
                 existUser·p0.999:  28.411 ms/op
                 existUser·p0.9999: 31.359 ms/op
                 existUser·p1.00:   32.571 ms/op

Iteration   2: 5.762 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.318 ms/op
                 existUser·p0.50:   5.423 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.233 ms/op
                 existUser·p0.99:   10.879 ms/op
                 existUser·p0.999:  18.006 ms/op
                 existUser·p0.9999: 35.288 ms/op
                 existUser·p1.00:   36.569 ms/op

Iteration   3: 5.615 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   6.955 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   11.076 ms/op
                 existUser·p0.999:  32.472 ms/op
                 existUser·p0.9999: 35.317 ms/op
                 existUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 167322
  mean =      5.735 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 49150 
    [ 5.000,  7.500) = 103504 
    [ 7.500, 10.000) = 11109 
    [10.000, 12.500) = 2544 
    [12.500, 15.000) = 498 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 65 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.258 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     26.837 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     36.612 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.248 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.343 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.313 ±(99.9%) 0.028 ms/op
Iteration   1: 6.256 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.985 ms/op
                 getUser·p0.50:   5.669 ms/op
                 getUser·p0.90:   8.315 ms/op
                 getUser·p0.95:   10.633 ms/op
                 getUser·p0.99:   15.385 ms/op
                 getUser·p0.999:  23.743 ms/op
                 getUser·p0.9999: 32.948 ms/op
                 getUser·p1.00:   35.848 ms/op

Iteration   2: 5.945 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   5.620 ms/op
                 getUser·p0.90:   7.397 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  30.698 ms/op
                 getUser·p0.9999: 49.340 ms/op
                 getUser·p1.00:   50.987 ms/op

Iteration   3: 5.887 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.765 ms/op
                 getUser·p0.50:   5.538 ms/op
                 getUser·p0.90:   7.193 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   11.403 ms/op
                 getUser·p0.999:  31.121 ms/op
                 getUser·p0.9999: 36.831 ms/op
                 getUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159147
  mean =      6.025 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 27610 
    [ 5.000, 10.000) = 126195 
    [10.000, 15.000) = 4437 
    [15.000, 20.000) = 658 
    [20.000, 25.000) = 73 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 87 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      7.512 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     13.009 ms/op
     p(99.9000) =     28.989 ms/op
     p(99.9900) =     47.710 ms/op
     p(99.9990) =     50.289 ms/op
     p(99.9999) =     50.987 ms/op
    p(100.0000) =     50.987 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.363 ±(99.9%) 0.413 ms/op
# Warmup Iteration   2: 8.652 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 7.259 ±(99.9%) 0.035 ms/op
Iteration   1: 8.415 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   7.492 ms/op
                 listUser·p0.90:   12.321 ms/op
                 listUser·p0.95:   14.123 ms/op
                 listUser·p0.99:   19.104 ms/op
                 listUser·p0.999:  31.719 ms/op
                 listUser·p0.9999: 43.148 ms/op
                 listUser·p1.00:   43.844 ms/op

Iteration   2: 7.560 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   3.015 ms/op
                 listUser·p0.50:   6.889 ms/op
                 listUser·p0.90:   10.093 ms/op
                 listUser·p0.95:   11.813 ms/op
                 listUser·p0.99:   16.171 ms/op
                 listUser·p0.999:  35.631 ms/op
                 listUser·p0.9999: 40.012 ms/op
                 listUser·p1.00:   40.698 ms/op

Iteration   3: 7.248 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   3.023 ms/op
                 listUser·p0.50:   6.627 ms/op
                 listUser·p0.90:   9.585 ms/op
                 listUser·p0.95:   11.370 ms/op
                 listUser·p0.99:   15.303 ms/op
                 listUser·p0.999:  37.996 ms/op
                 listUser·p0.9999: 41.692 ms/op
                 listUser·p1.00:   42.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 124447
  mean =      7.711 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1344 
    [ 5.000, 10.000) = 107181 
    [10.000, 15.000) = 13418 
    [15.000, 20.000) = 2012 
    [20.000, 25.000) = 216 
    [25.000, 30.000) = 59 
    [30.000, 35.000) = 68 
    [35.000, 40.000) = 101 
    [40.000, 45.000) = 48 

  Percentiles, ms/op:
      p(0.0000) =      2.048 ms/op
     p(50.0000) =      6.922 ms/op
     p(90.0000) =     10.699 ms/op
     p(95.0000) =     12.665 ms/op
     p(99.0000) =     17.039 ms/op
     p(99.9000) =     36.635 ms/op
     p(99.9900) =     42.438 ms/op
     p(99.9990) =     43.828 ms/op
     p(99.9999) =     43.844 ms/op
    p(100.0000) =     43.844 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.122 ± 2.238  ops/ms
ClientPb.existUser                       thrpt       3   5.606 ± 0.784  ops/ms
ClientPb.getUser                         thrpt       3   5.430 ± 3.243  ops/ms
ClientPb.listUser                        thrpt       3   4.588 ± 1.695  ops/ms
ClientPb.createUser                       avgt       3   5.929 ± 1.117   ms/op
ClientPb.existUser                        avgt       3   5.663 ± 1.064   ms/op
ClientPb.getUser                          avgt       3   6.141 ± 1.330   ms/op
ClientPb.listUser                         avgt       3   7.044 ± 0.600   ms/op
ClientPb.createUser                     sample  161902   5.928 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.520           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.880           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.059           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.624           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.115           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.421           ms/op
ClientPb.existUser                      sample  167322   5.735 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.493           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.438           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.239           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.837           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.193           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.700           ms/op
ClientPb.getUser                        sample  159147   6.025 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.512           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.110           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.009           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.989           ms/op
ClientPb.getUser:getUser·p0.9999        sample          47.710           ms/op
ClientPb.getUser:getUser·p1.00          sample          50.987           ms/op
ClientPb.listUser                       sample  124447   7.711 ± 0.025   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.048           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.90        sample          10.699           ms/op
ClientPb.listUser:listUser·p0.95        sample          12.665           ms/op
ClientPb.listUser:listUser·p0.99        sample          17.039           ms/op
ClientPb.listUser:listUser·p0.999       sample          36.635           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.438           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.844           ms/op
