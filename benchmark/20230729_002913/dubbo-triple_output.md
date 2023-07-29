# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.992 ops/ms
# Warmup Iteration   2: 2.021 ops/ms
# Warmup Iteration   3: 4.012 ops/ms
Iteration   1: 5.229 ops/ms
Iteration   2: 5.377 ops/ms
Iteration   3: 5.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.324 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (5.229, 5.324, 5.377), stdev = 0.083
  CI (99.9%): [3.819, 6.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.463 ops/ms
# Warmup Iteration   2: 4.295 ops/ms
# Warmup Iteration   3: 5.445 ops/ms
Iteration   1: 5.283 ops/ms
Iteration   2: 5.594 ops/ms
Iteration   3: 5.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.485 ±(99.9%) 3.195 ops/ms [Average]
  (min, avg, max) = (5.283, 5.485, 5.594), stdev = 0.175
  CI (99.9%): [2.290, 8.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.253 ops/ms
# Warmup Iteration   2: 3.957 ops/ms
# Warmup Iteration   3: 5.256 ops/ms
Iteration   1: 5.186 ops/ms
Iteration   2: 5.293 ops/ms
Iteration   3: 5.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.223 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (5.186, 5.223, 5.293), stdev = 0.061
  CI (99.9%): [4.116, 6.329] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.468 ops/ms
# Warmup Iteration   2: 3.752 ops/ms
# Warmup Iteration   3: 4.642 ops/ms
Iteration   1: 4.455 ops/ms
Iteration   2: 4.513 ops/ms
Iteration   3: 4.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.555 ±(99.9%) 2.320 ops/ms [Average]
  (min, avg, max) = (4.455, 4.555, 4.698), stdev = 0.127
  CI (99.9%): [2.235, 6.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 22.716 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 7.968 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.331 ±(99.9%) 0.013 ms/op
Iteration   1: 6.008 ±(99.9%) 0.020 ms/op
Iteration   2: 5.884 ±(99.9%) 0.013 ms/op
Iteration   3: 5.876 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.923 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (5.876, 5.923, 6.008), stdev = 0.074
  CI (99.9%): [4.571, 7.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 19.750 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.438 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.770 ±(99.9%) 0.012 ms/op
Iteration   1: 5.812 ±(99.9%) 0.010 ms/op
Iteration   2: 5.644 ±(99.9%) 0.009 ms/op
Iteration   3: 5.631 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.696 ±(99.9%) 1.838 ms/op [Average]
  (min, avg, max) = (5.631, 5.696, 5.812), stdev = 0.101
  CI (99.9%): [3.857, 7.534] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.279 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 7.457 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.054 ±(99.9%) 0.010 ms/op
Iteration   1: 5.735 ±(99.9%) 0.016 ms/op
Iteration   2: 5.719 ±(99.9%) 0.020 ms/op
Iteration   3: 5.733 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.729 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (5.719, 5.729, 5.735), stdev = 0.009
  CI (99.9%): [5.563, 5.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.022 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 8.826 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 7.514 ±(99.9%) 0.016 ms/op
Iteration   1: 6.992 ±(99.9%) 0.020 ms/op
Iteration   2: 6.959 ±(99.9%) 0.019 ms/op
Iteration   3: 7.046 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.999 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (6.959, 6.999, 7.046), stdev = 0.044
  CI (99.9%): [6.201, 7.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 21.947 ±(99.9%) 0.407 ms/op
# Warmup Iteration   2: 7.818 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.419 ±(99.9%) 0.033 ms/op
Iteration   1: 5.919 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.560 ms/op
                 createUser·p0.50:   5.546 ms/op
                 createUser·p0.90:   7.619 ms/op
                 createUser·p0.95:   8.750 ms/op
                 createUser·p0.99:   11.469 ms/op
                 createUser·p0.999:  16.416 ms/op
                 createUser·p0.9999: 26.961 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 6.008 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   5.661 ms/op
                 createUser·p0.90:   7.676 ms/op
                 createUser·p0.95:   8.733 ms/op
                 createUser·p0.99:   11.141 ms/op
                 createUser·p0.999:  26.461 ms/op
                 createUser·p0.9999: 31.604 ms/op
                 createUser·p1.00:   32.047 ms/op

Iteration   3: 5.927 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.564 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.587 ms/op
                 createUser·p0.95:   8.864 ms/op
                 createUser·p0.99:   11.665 ms/op
                 createUser·p0.999:  27.001 ms/op
                 createUser·p0.9999: 30.048 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161200
  mean =      5.951 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 36282 
    [ 5.000,  7.500) = 107381 
    [ 7.500, 10.000) = 13797 
    [10.000, 12.500) = 2806 
    [12.500, 15.000) = 634 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.331 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     11.419 ms/op
     p(99.9000) =     20.408 ms/op
     p(99.9900) =     30.888 ms/op
     p(99.9990) =     32.607 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.328 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.264 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.906 ±(99.9%) 0.025 ms/op
Iteration   1: 5.788 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.232 ms/op
                 existUser·p0.50:   5.431 ms/op
                 existUser·p0.90:   7.381 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   11.141 ms/op
                 existUser·p0.999:  27.932 ms/op
                 existUser·p0.9999: 30.424 ms/op
                 existUser·p1.00:   30.966 ms/op

Iteration   2: 5.596 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.159 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  27.258 ms/op
                 existUser·p0.9999: 31.434 ms/op
                 existUser·p1.00:   32.211 ms/op

Iteration   3: 5.717 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.527 ms/op
                 existUser·p0.50:   5.325 ms/op
                 existUser·p0.90:   7.127 ms/op
                 existUser·p0.95:   8.364 ms/op
                 existUser·p0.99:   12.042 ms/op
                 existUser·p0.999:  17.224 ms/op
                 existUser·p0.9999: 38.261 ms/op
                 existUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168353
  mean =      5.699 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 50771 
    [ 5.000,  7.500) = 103997 
    [ 7.500, 10.000) = 10282 
    [10.000, 12.500) = 2234 
    [12.500, 15.000) = 652 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     26.694 ms/op
     p(99.9900) =     37.290 ms/op
     p(99.9990) =     38.639 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 21.081 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.181 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.090 ±(99.9%) 0.026 ms/op
Iteration   1: 6.005 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.699 ms/op
                 getUser·p0.50:   5.587 ms/op
                 getUser·p0.90:   7.807 ms/op
                 getUser·p0.95:   9.241 ms/op
                 getUser·p0.99:   12.403 ms/op
                 getUser·p0.999:  17.695 ms/op
                 getUser·p0.9999: 31.796 ms/op
                 getUser·p1.00:   32.539 ms/op

Iteration   2: 5.933 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.609 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   9.028 ms/op
                 getUser·p0.99:   12.665 ms/op
                 getUser·p0.999:  26.963 ms/op
                 getUser·p0.9999: 30.634 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   3: 5.784 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   5.407 ms/op
                 getUser·p0.90:   7.463 ms/op
                 getUser·p0.95:   8.634 ms/op
                 getUser·p0.99:   10.994 ms/op
                 getUser·p0.999:  30.367 ms/op
                 getUser·p0.9999: 34.367 ms/op
                 getUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162482
  mean =      5.906 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 38939 
    [ 5.000,  7.500) = 106146 
    [ 7.500, 10.000) = 12906 
    [10.000, 12.500) = 3138 
    [12.500, 15.000) = 812 
    [15.000, 17.500) = 264 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 82 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.962 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     26.248 ms/op
     p(99.9900) =     32.367 ms/op
     p(99.9990) =     34.628 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.084 ±(99.9%) 0.420 ms/op
# Warmup Iteration   2: 8.299 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 7.086 ±(99.9%) 0.034 ms/op
Iteration   1: 7.116 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.478 ms/op
                 listUser·p0.50:   6.627 ms/op
                 listUser·p0.90:   9.110 ms/op
                 listUser·p0.95:   10.535 ms/op
                 listUser·p0.99:   13.615 ms/op
                 listUser·p0.999:  30.153 ms/op
                 listUser·p0.9999: 33.456 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   2: 7.012 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.765 ms/op
                 listUser·p0.95:   10.282 ms/op
                 listUser·p0.99:   13.353 ms/op
                 listUser·p0.999:  35.635 ms/op
                 listUser·p0.9999: 39.707 ms/op
                 listUser·p1.00:   40.108 ms/op

Iteration   3: 6.873 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.346 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   12.763 ms/op
                 listUser·p0.999:  30.900 ms/op
                 listUser·p0.9999: 36.517 ms/op
                 listUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137065
  mean =      6.999 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2329 
    [ 5.000, 10.000) = 127028 
    [10.000, 15.000) = 7046 
    [15.000, 20.000) = 316 
    [20.000, 25.000) = 66 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 121 
    [35.000, 40.000) = 58 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      6.554 ms/op
     p(90.0000) =      8.782 ms/op
     p(95.0000) =     10.240 ms/op
     p(99.0000) =     13.271 ms/op
     p(99.9000) =     31.457 ms/op
     p(99.9900) =     39.518 ms/op
     p(99.9990) =     40.715 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.324 ± 1.505  ops/ms
ClientPb.existUser                       thrpt       3   5.485 ± 3.195  ops/ms
ClientPb.getUser                         thrpt       3   5.223 ± 1.107  ops/ms
ClientPb.listUser                        thrpt       3   4.555 ± 2.320  ops/ms
ClientPb.createUser                       avgt       3   5.923 ± 1.352   ms/op
ClientPb.existUser                        avgt       3   5.696 ± 1.838   ms/op
ClientPb.getUser                          avgt       3   5.729 ± 0.166   ms/op
ClientPb.listUser                         avgt       3   6.999 ± 0.798   ms/op
ClientPb.createUser                     sample  161200   5.951 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.782           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.419           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.408           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.888           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  168353   5.699 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.232           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.184           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.364           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.403           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.694           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.290           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.863           ms/op
ClientPb.getUser                        sample  162482   5.906 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.919           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.962           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.026           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.248           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.367           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  137065   6.999 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.372           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.240           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.271           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.457           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.763           ms/op
