# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.182 ops/ms
# Warmup Iteration   2: 2.566 ops/ms
# Warmup Iteration   3: 5.496 ops/ms
Iteration   1: 5.810 ops/ms
Iteration   2: 5.672 ops/ms
Iteration   3: 5.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.788 ±(99.9%) 1.947 ops/ms [Average]
  (min, avg, max) = (5.672, 5.788, 5.882), stdev = 0.107
  CI (99.9%): [3.841, 7.735] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.724 ops/ms
# Warmup Iteration   2: 5.299 ops/ms
# Warmup Iteration   3: 5.964 ops/ms
Iteration   1: 6.283 ops/ms
Iteration   2: 6.320 ops/ms
Iteration   3: 6.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.334 ±(99.9%) 1.075 ops/ms [Average]
  (min, avg, max) = (6.283, 6.334, 6.398), stdev = 0.059
  CI (99.9%): [5.258, 7.409] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.564 ops/ms
# Warmup Iteration   2: 4.604 ops/ms
# Warmup Iteration   3: 5.763 ops/ms
Iteration   1: 5.872 ops/ms
Iteration   2: 5.798 ops/ms
Iteration   3: 5.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.864 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (5.798, 5.864, 5.922), stdev = 0.062
  CI (99.9%): [4.726, 7.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.437 ops/ms
# Warmup Iteration   2: 4.191 ops/ms
# Warmup Iteration   3: 5.303 ops/ms
Iteration   1: 5.086 ops/ms
Iteration   2: 5.069 ops/ms
Iteration   3: 5.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.103 ±(99.9%) 0.822 ops/ms [Average]
  (min, avg, max) = (5.069, 5.103, 5.154), stdev = 0.045
  CI (99.9%): [4.281, 5.925] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 18.131 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.667 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.924 ±(99.9%) 0.012 ms/op
Iteration   1: 5.378 ±(99.9%) 0.016 ms/op
Iteration   2: 5.506 ±(99.9%) 0.013 ms/op
Iteration   3: 5.522 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.469 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (5.378, 5.469, 5.522), stdev = 0.079
  CI (99.9%): [4.031, 6.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 18.053 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.418 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.425 ±(99.9%) 0.010 ms/op
Iteration   1: 4.946 ±(99.9%) 0.020 ms/op
Iteration   2: 4.978 ±(99.9%) 0.024 ms/op
Iteration   3: 5.103 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.009 ±(99.9%) 1.508 ms/op [Average]
  (min, avg, max) = (4.946, 5.009, 5.103), stdev = 0.083
  CI (99.9%): [3.501, 6.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 19.303 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.335 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.365 ±(99.9%) 0.015 ms/op
Iteration   1: 5.504 ±(99.9%) 0.009 ms/op
Iteration   2: 5.404 ±(99.9%) 0.013 ms/op
Iteration   3: 5.735 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.547 ±(99.9%) 3.095 ms/op [Average]
  (min, avg, max) = (5.404, 5.547, 5.735), stdev = 0.170
  CI (99.9%): [2.452, 8.642] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.174 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 8.111 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.365 ±(99.9%) 0.015 ms/op
Iteration   1: 6.336 ±(99.9%) 0.012 ms/op
Iteration   2: 6.179 ±(99.9%) 0.020 ms/op
Iteration   3: 6.227 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.247 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (6.179, 6.247, 6.336), stdev = 0.080
  CI (99.9%): [4.785, 7.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.958 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 7.025 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.909 ±(99.9%) 0.026 ms/op
Iteration   1: 5.558 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.576 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   8.028 ms/op
                 createUser·p0.99:   11.141 ms/op
                 createUser·p0.999:  23.477 ms/op
                 createUser·p0.9999: 29.278 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   2: 5.511 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  25.968 ms/op
                 createUser·p0.9999: 34.026 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   3: 5.529 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.306 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.471 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  14.434 ms/op
                 createUser·p0.9999: 28.817 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173472
  mean =      5.532 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 60504 
    [ 5.000,  7.500) = 103136 
    [ 7.500, 10.000) = 7617 
    [10.000, 12.500) = 1547 
    [12.500, 15.000) = 356 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     16.360 ms/op
     p(99.9900) =     30.352 ms/op
     p(99.9990) =     34.572 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.479 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.884 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.226 ±(99.9%) 0.017 ms/op
Iteration   1: 5.232 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.315 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  14.628 ms/op
                 existUser·p0.9999: 29.557 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   2: 5.260 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.225 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  28.689 ms/op
                 existUser·p0.9999: 34.617 ms/op
                 existUser·p1.00:   34.865 ms/op

Iteration   3: 5.568 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.991 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   7.160 ms/op
                 existUser·p0.95:   8.053 ms/op
                 existUser·p0.99:   10.469 ms/op
                 existUser·p0.999:  25.833 ms/op
                 existUser·p0.9999: 32.222 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179464
  mean =      5.349 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 81677 
    [ 5.000,  7.500) = 88240 
    [ 7.500, 10.000) = 8078 
    [10.000, 12.500) = 1068 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     17.024 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     34.813 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.161 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 6.144 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.690 ±(99.9%) 0.022 ms/op
Iteration   1: 5.429 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   12.485 ms/op
                 getUser·p0.999:  22.552 ms/op
                 getUser·p0.9999: 29.167 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   2: 5.573 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   6.734 ms/op
                 getUser·p0.95:   7.766 ms/op
                 getUser·p0.99:   10.796 ms/op
                 getUser·p0.999:  25.120 ms/op
                 getUser·p0.9999: 29.041 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   3: 5.516 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.306 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   7.820 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  26.182 ms/op
                 getUser·p0.9999: 30.474 ms/op
                 getUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174263
  mean =      5.506 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 67885 
    [ 5.000,  7.500) = 95352 
    [ 7.500, 10.000) = 7957 
    [10.000, 12.500) = 2045 
    [12.500, 15.000) = 512 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     24.164 ms/op
     p(99.9900) =     29.543 ms/op
     p(99.9990) =     30.991 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.254 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.593 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.480 ±(99.9%) 0.026 ms/op
Iteration   1: 6.688 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.342 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   10.371 ms/op
                 listUser·p0.99:   13.631 ms/op
                 listUser·p0.999:  26.221 ms/op
                 listUser·p0.9999: 30.477 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   2: 6.535 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   13.083 ms/op
                 listUser·p0.999:  29.426 ms/op
                 listUser·p0.9999: 32.545 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   3: 6.370 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  23.920 ms/op
                 listUser·p0.9999: 27.754 ms/op
                 listUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146985
  mean =      6.528 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 5290 
    [ 5.000,  7.500) = 123095 
    [ 7.500, 10.000) = 12824 
    [10.000, 12.500) = 3940 
    [12.500, 15.000) = 1061 
    [15.000, 17.500) = 407 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      6.160 ms/op
     p(90.0000) =      7.840 ms/op
     p(95.0000) =      9.437 ms/op
     p(99.0000) =     13.028 ms/op
     p(99.9000) =     26.640 ms/op
     p(99.9900) =     31.431 ms/op
     p(99.9990) =     32.932 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.788 ± 1.947  ops/ms
ClientPb.existUser                       thrpt       3   6.334 ± 1.075  ops/ms
ClientPb.getUser                         thrpt       3   5.864 ± 1.138  ops/ms
ClientPb.listUser                        thrpt       3   5.103 ± 0.822  ops/ms
ClientPb.createUser                       avgt       3   5.469 ± 1.438   ms/op
ClientPb.existUser                        avgt       3   5.009 ± 1.508   ms/op
ClientPb.getUser                          avgt       3   5.547 ± 3.095   ms/op
ClientPb.listUser                         avgt       3   6.247 ± 1.462   ms/op
ClientPb.createUser                     sample  173472   5.532 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.692           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.360           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.352           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  179464   5.349 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.714           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.701           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.578           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.683           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.024           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.047           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.865           ms/op
ClientPb.getUser                        sample  174263   5.506 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.984           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.922           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.190           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.164           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.543           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.064           ms/op
ClientPb.listUser                       sample  146985   6.528 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.840           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.437           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.028           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.640           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.431           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.932           ms/op
