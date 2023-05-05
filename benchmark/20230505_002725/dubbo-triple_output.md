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
# Warmup Iteration   1: 2.055 ops/ms
# Warmup Iteration   2: 5.319 ops/ms
# Warmup Iteration   3: 8.490 ops/ms
Iteration   1: 9.247 ops/ms
Iteration   2: 9.565 ops/ms
Iteration   3: 9.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.388 ±(99.9%) 2.952 ops/ms [Average]
  (min, avg, max) = (9.247, 9.388, 9.565), stdev = 0.162
  CI (99.9%): [6.436, 12.340] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.208 ops/ms
# Warmup Iteration   2: 8.734 ops/ms
# Warmup Iteration   3: 9.556 ops/ms
Iteration   1: 9.689 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 9.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.789 ±(99.9%) 3.592 ops/ms [Average]
  (min, avg, max) = (9.662, 9.789, 10.016), stdev = 0.197
  CI (99.9%): [6.196, 13.381] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.993 ops/ms
# Warmup Iteration   2: 8.179 ops/ms
# Warmup Iteration   3: 8.972 ops/ms
Iteration   1: 9.030 ops/ms
Iteration   2: 9.265 ops/ms
Iteration   3: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.243 ±(99.9%) 3.698 ops/ms [Average]
  (min, avg, max) = (9.030, 9.243, 9.433), stdev = 0.203
  CI (99.9%): [5.545, 12.940] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 7.182 ops/ms
# Warmup Iteration   3: 7.838 ops/ms
Iteration   1: 7.920 ops/ms
Iteration   2: 7.682 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.853 ±(99.9%) 2.719 ops/ms [Average]
  (min, avg, max) = (7.682, 7.853, 7.957), stdev = 0.149
  CI (99.9%): [5.134, 10.572] (assumes normal distribution)


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
# Warmup Iteration   1: 9.688 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.006 ms/op
Iteration   1: 3.383 ±(99.9%) 0.008 ms/op
Iteration   2: 3.374 ±(99.9%) 0.005 ms/op
Iteration   3: 3.308 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.355 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.308, 3.355, 3.383), stdev = 0.041
  CI (99.9%): [2.602, 4.107] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.973 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.004 ms/op
Iteration   1: 3.283 ±(99.9%) 0.008 ms/op
Iteration   2: 3.174 ±(99.9%) 0.005 ms/op
Iteration   3: 3.270 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.242 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (3.174, 3.242, 3.283), stdev = 0.059
  CI (99.9%): [2.160, 4.324] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.333 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.005 ms/op
Iteration   1: 3.543 ±(99.9%) 0.003 ms/op
Iteration   2: 3.513 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.473 ±(99.9%) 1.745 ms/op [Average]
  (min, avg, max) = (3.364, 3.473, 3.543), stdev = 0.096
  CI (99.9%): [1.728, 5.218] (assumes normal distribution)


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
# Warmup Iteration   1: 10.978 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.014 ms/op
Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
Iteration   2: 3.874 ±(99.9%) 0.014 ms/op
Iteration   3: 4.046 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.979 ±(99.9%) 1.676 ms/op [Average]
  (min, avg, max) = (3.874, 3.979, 4.046), stdev = 0.092
  CI (99.9%): [2.303, 5.655] (assumes normal distribution)


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
# Warmup Iteration   1: 10.805 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.014 ms/op
Iteration   1: 3.513 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.180 ms/op
                 createUser·p0.999:  19.036 ms/op
                 createUser·p0.9999: 24.507 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.382 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 27.969 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  17.099 ms/op
                 createUser·p0.9999: 27.639 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277786
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4076 
    [ 2.500,  5.000) = 267439 
    [ 5.000,  7.500) = 5150 
    [ 7.500, 10.000) = 547 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     17.470 ms/op
     p(99.9900) =     27.663 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 9.109 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
Iteration   1: 3.349 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  8.849 ms/op
                 existUser·p0.9999: 23.280 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 3.503 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  22.982 ms/op
                 existUser·p0.9999: 25.745 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.724 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.640 ms/op
                 existUser·p0.999:  17.633 ms/op
                 existUser·p0.9999: 28.418 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282744
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6439 
    [ 2.500,  5.000) = 268820 
    [ 5.000,  7.500) = 6647 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     27.054 ms/op
     p(99.9990) =     28.776 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 10.999 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
Iteration   1: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  15.257 ms/op
                 getUser·p0.9999: 25.829 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 3.496 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  24.379 ms/op
                 getUser·p0.9999: 30.099 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  20.185 ms/op
                 getUser·p0.9999: 28.344 ms/op
                 getUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274772
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8800 
    [ 2.500,  5.000) = 257189 
    [ 5.000,  7.500) = 7526 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     15.810 ms/op
     p(99.9900) =     28.230 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 11.435 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.014 ms/op
Iteration   1: 4.109 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.259 ms/op
                 listUser·p0.999:  21.277 ms/op
                 listUser·p0.9999: 27.329 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.108 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 17.374 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236246
  mean =      4.064 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 227235 
    [ 5.000,  7.500) = 6892 
    [ 7.500, 10.000) = 1093 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     28.178 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.388 ± 2.952  ops/ms
ClientPb.existUser                       thrpt       3   9.789 ± 3.592  ops/ms
ClientPb.getUser                         thrpt       3   9.243 ± 3.698  ops/ms
ClientPb.listUser                        thrpt       3   7.853 ± 2.719  ops/ms
ClientPb.createUser                       avgt       3   3.355 ± 0.752   ms/op
ClientPb.existUser                        avgt       3   3.242 ± 1.082   ms/op
ClientPb.getUser                          avgt       3   3.473 ± 1.745   ms/op
ClientPb.listUser                         avgt       3   3.979 ± 1.676   ms/op
ClientPb.createUser                     sample  277786   3.454 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.419           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.087           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.470           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.663           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  282744   3.393 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.054           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  274772   3.493 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.020           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.230           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  236246   4.064 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.334           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.756           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
