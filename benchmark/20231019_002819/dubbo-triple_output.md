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
# Warmup Iteration   1: 0.923 ops/ms
# Warmup Iteration   2: 2.076 ops/ms
# Warmup Iteration   3: 4.447 ops/ms
Iteration   1: 5.163 ops/ms
Iteration   2: 5.017 ops/ms
Iteration   3: 5.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.216 ±(99.9%) 4.199 ops/ms [Average]
  (min, avg, max) = (5.017, 5.216, 5.468), stdev = 0.230
  CI (99.9%): [1.017, 9.415] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.448 ops/ms
# Warmup Iteration   2: 3.774 ops/ms
# Warmup Iteration   3: 5.490 ops/ms
Iteration   1: 5.732 ops/ms
Iteration   2: 5.837 ops/ms
Iteration   3: 5.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.835 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (5.732, 5.835, 5.936), stdev = 0.102
  CI (99.9%): [3.970, 7.701] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.453 ops/ms
# Warmup Iteration   2: 4.364 ops/ms
# Warmup Iteration   3: 5.426 ops/ms
Iteration   1: 5.591 ops/ms
Iteration   2: 5.517 ops/ms
Iteration   3: 5.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.526 ±(99.9%) 1.126 ops/ms [Average]
  (min, avg, max) = (5.469, 5.526, 5.591), stdev = 0.062
  CI (99.9%): [4.400, 6.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.368 ops/ms
# Warmup Iteration   2: 3.498 ops/ms
# Warmup Iteration   3: 4.469 ops/ms
Iteration   1: 4.741 ops/ms
Iteration   2: 4.831 ops/ms
Iteration   3: 4.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.762 ±(99.9%) 1.110 ops/ms [Average]
  (min, avg, max) = (4.715, 4.762, 4.831), stdev = 0.061
  CI (99.9%): [3.652, 5.872] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.430 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 7.336 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.115 ±(99.9%) 0.011 ms/op
Iteration   1: 5.895 ±(99.9%) 0.012 ms/op
Iteration   2: 5.940 ±(99.9%) 0.016 ms/op
Iteration   3: 5.833 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.890 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (5.833, 5.890, 5.940), stdev = 0.054
  CI (99.9%): [4.910, 6.869] (assumes normal distribution)


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
# Warmup Iteration   1: 17.721 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.589 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.522 ±(99.9%) 0.014 ms/op
Iteration   1: 5.521 ±(99.9%) 0.010 ms/op
Iteration   2: 5.421 ±(99.9%) 0.011 ms/op
Iteration   3: 5.626 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.523 ±(99.9%) 1.873 ms/op [Average]
  (min, avg, max) = (5.421, 5.523, 5.626), stdev = 0.103
  CI (99.9%): [3.650, 7.396] (assumes normal distribution)


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
# Warmup Iteration   1: 19.685 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.854 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.997 ±(99.9%) 0.011 ms/op
Iteration   1: 5.929 ±(99.9%) 0.008 ms/op
Iteration   2: 5.790 ±(99.9%) 0.009 ms/op
Iteration   3: 5.698 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.806 ±(99.9%) 2.125 ms/op [Average]
  (min, avg, max) = (5.698, 5.806, 5.929), stdev = 0.116
  CI (99.9%): [3.681, 7.930] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 21.555 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 9.113 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.822 ±(99.9%) 0.019 ms/op
Iteration   1: 6.824 ±(99.9%) 0.012 ms/op
Iteration   2: 6.650 ±(99.9%) 0.022 ms/op
Iteration   3: 6.784 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.753 ±(99.9%) 1.666 ms/op [Average]
  (min, avg, max) = (6.650, 6.753, 6.824), stdev = 0.091
  CI (99.9%): [5.087, 8.418] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.476 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.712 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.607 ±(99.9%) 0.033 ms/op
Iteration   1: 5.828 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.662 ms/op
                 createUser·p0.50:   5.546 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.151 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  16.007 ms/op
                 createUser·p0.9999: 28.627 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   2: 5.779 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.499 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   7.766 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  29.089 ms/op
                 createUser·p0.9999: 33.844 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   3: 5.641 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  30.853 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166858
  mean =      5.748 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 42784 
    [ 5.000,  7.500) = 113034 
    [ 7.500, 10.000) = 8774 
    [10.000, 12.500) = 1498 
    [12.500, 15.000) = 447 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      7.881 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     22.624 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 17.928 ±(99.9%) 0.364 ms/op
# Warmup Iteration   2: 6.807 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.716 ±(99.9%) 0.024 ms/op
Iteration   1: 5.721 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   5.366 ms/op
                 existUser·p0.90:   7.168 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   11.862 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 28.479 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   2: 5.572 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.556 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   7.799 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  28.004 ms/op
                 existUser·p0.9999: 32.032 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   3: 5.421 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.286 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.373 ms/op
                 existUser·p0.99:   10.247 ms/op
                 existUser·p0.999:  32.635 ms/op
                 existUser·p0.9999: 36.968 ms/op
                 existUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172329
  mean =      5.568 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 60322 
    [ 5.000,  7.500) = 101454 
    [ 7.500, 10.000) = 7521 
    [10.000, 12.500) = 1884 
    [12.500, 15.000) = 760 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 38 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     37.530 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 19.604 ±(99.9%) 0.371 ms/op
# Warmup Iteration   2: 8.134 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 5.898 ±(99.9%) 0.021 ms/op
Iteration   1: 5.782 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.519 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   7.799 ms/op
                 getUser·p0.99:   10.846 ms/op
                 getUser·p0.999:  26.972 ms/op
                 getUser·p0.9999: 33.520 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   2: 5.897 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.974 ms/op
                 getUser·p0.50:   5.612 ms/op
                 getUser·p0.90:   7.053 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   11.578 ms/op
                 getUser·p0.999:  27.558 ms/op
                 getUser·p0.9999: 30.264 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   3: 5.760 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.765 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   8.053 ms/op
                 getUser·p0.99:   11.568 ms/op
                 getUser·p0.999:  28.686 ms/op
                 getUser·p0.9999: 32.535 ms/op
                 getUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165024
  mean =      5.812 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 33491 
    [ 5.000,  7.500) = 120733 
    [ 7.500, 10.000) = 7584 
    [10.000, 12.500) = 2176 
    [12.500, 15.000) = 664 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 72 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.519 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     27.558 ms/op
     p(99.9900) =     32.588 ms/op
     p(99.9990) =     34.187 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 19.806 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 8.295 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.821 ±(99.9%) 0.027 ms/op
Iteration   1: 6.929 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   6.496 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   12.985 ms/op
                 listUser·p0.999:  28.541 ms/op
                 listUser·p0.9999: 31.883 ms/op
                 listUser·p1.00:   33.063 ms/op

Iteration   2: 6.858 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   13.009 ms/op
                 listUser·p0.999:  30.847 ms/op
                 listUser·p0.9999: 37.224 ms/op
                 listUser·p1.00:   37.421 ms/op

Iteration   3: 6.814 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.974 ms/op
                 listUser·p0.50:   6.472 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   14.008 ms/op
                 listUser·p0.999:  27.495 ms/op
                 listUser·p0.9999: 33.571 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139755
  mean =      6.867 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 2590 
    [ 5.000,  7.500) = 110780 
    [ 7.500, 10.000) = 19642 
    [10.000, 12.500) = 4900 
    [12.500, 15.000) = 1070 
    [15.000, 17.500) = 284 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      6.463 ms/op
     p(90.0000) =      8.372 ms/op
     p(95.0000) =      9.880 ms/op
     p(99.0000) =     13.222 ms/op
     p(99.9000) =     29.073 ms/op
     p(99.9900) =     34.342 ms/op
     p(99.9990) =     37.395 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.216 ± 4.199  ops/ms
ClientPb.existUser                       thrpt       3   5.835 ± 1.866  ops/ms
ClientPb.getUser                         thrpt       3   5.526 ± 1.126  ops/ms
ClientPb.listUser                        thrpt       3   4.762 ± 1.110  ops/ms
ClientPb.createUser                       avgt       3   5.890 ± 0.980   ms/op
ClientPb.existUser                        avgt       3   5.523 ± 1.873   ms/op
ClientPb.getUser                          avgt       3   5.806 ± 2.125   ms/op
ClientPb.listUser                         avgt       3   6.753 ± 1.666   ms/op
ClientPb.createUser                     sample  166858   5.748 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.444           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.881           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.624           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  172329   5.568 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.872           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.816           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.897           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.321           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.677           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.652           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  165024   5.812 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.971           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.354           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.558           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.588           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.996           ms/op
ClientPb.listUser                       sample  139755   6.867 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.688           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.463           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.880           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.222           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.342           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.421           ms/op
